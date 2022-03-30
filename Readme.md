Projeto para aprofudar meus conhecimentos na CLI do github.


## Comandos:
* mkdir: make dir
* clear
* pwd : caminho completo
* ls | dir : -a (adiciona arquivos ocultos)
* echo hello  : imprime na tela hello
* echo hello > hello.txt  : cria o arquivo com o texto (> redireciona o fluxo) 
* del 'path' : se usar em pasta, limpa todo o conteudo dela
* windows: rmdir 'path' /S /Q : removeDir remove a pasta. > /S /Q são flags
* linux: rm -rf 'path' : remove (-r remove subpastas dentro | -f executa sem perguntas)


### Comandos sha1:
* openssl sha1 sha1-test.html  > generates sha1 code: 418fba639dc2a7efde564c9f13b8dcdcde44ee71


### Comandos do GIT:
* Criar chave ssh:
  * ``ssh-keygen -t ed25519 -C YOUR_EMAIL`` - -C in uppercase
  * ir até a pasta criada c:/User/'user'/.ssh/
  * colocar a chave publica (.pub) no github
  * ``eval $(ssh-agent -s)`` - recebe um numero do processo
  * ``ssh-add c:/Users/'user'/.ssh/id_ed25519`` - passar a chave privada (irá pedir a senha)
* Primeiros comandos:
  * `git config --global user.email "YOUR_EMAIL"` - utilize as aspas
  * `git config --global user.name YOUR_NAME`

* `git init` - inicia repo
* `git add` - 
* `git commit` -

## Notas:
* silence on success: não avisa nada quando o comando dá certo.
