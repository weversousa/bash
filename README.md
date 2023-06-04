# bash

## Bash Custom

Eu gosto de criar um arquivo separado [.bash_custom](./.bash_custom) e chamá-lo dentro do arquivo `.bashrc`, dessa forma eu modifico o menos possível no arquivo original do sistema.

Mas para o arquivo `.bashrc` executar o que está dentro do outro arquivo é preciso inserir o código abaixo dentro dele.

```bash
 if [ -f ~/.bash_custom ]; then
     . ~/.bash_custom
 fi
```
