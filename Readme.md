# Git CLI

Projeto para aprofudar meus conhecimentos na CLI do github.
Curso realizado na DIO. Digital inovation one
Projeto finalizado com sucesso!

<a href="https://www.dio.me/certificate/64F1DD23/share" target="_blank">
  <p align="center">
    <img width="80%" src="./certificado.png" alt="certificado do luiz claudio, de conclusão do curso 'git e github' fornecido pela DIO (digital inovation one)"/>
  </p>
</a>

---

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
* mv 'arquivo' 'destino' : mover arquivo


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

* Comitar Uma mudança:
  * `git add *` - adiciona todas as mudanças
  * `git commit -m "TEXTO_DO_COMMIT"` - commita

* Outros comandos:
  * `git init` - inicia repo
  * `git status` - ve as mudanças do seu repo (um dos comandos mais importantes)
  * `git push origin master` - só funciona quando há o repositorio já criado no github

## Notas:
* silence on success: não avisa nada quando o comando dá certo.
