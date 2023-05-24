# Git-digital-course2
## Aprendiendo a usar git 
## Comandos de git:
* git clone caminho.... (clonar a pasta ao pc)
* git status ---> estado do arquivo (modificacao etc..)
* git diff ----> mostra as diferencas realizadas no arquivo
* git diff --staged ----> igual ao anterior solo si ya paso al estado final
* git log ---> Mostra Historico dos commit do arquivo na pasta
* git commit -m "comentario"----> Aceptar y guardar el arquivo
## Uso do comando restore
* git log ---> historico das alteracoes no commit
* git restore nome_do_arquivo --> Para arquivos modificados(nao no add ou commit)
* git restore --staged ---> Para arquivos que estao ataged (coloca o arquivo no modified)


## Subir online na plataforma github
* git remote ---> nome do repositorio
* git push (nome obtodo do remote) (nome da Branch canto inferior desta tela)
* git push ---> Disponibilizar online

## Comandos na nuvem (github)
* git pull ---> no pc ele combina a nuvem com o arquivo
* git fetch ---> serve para ver lo que esta en la nuve porem solo em peso resumido para usa el siguiente comando
* git diff nome_remoto/branck ---> Com este comando si podemos ver todo lo nuevo antes de actualizar oring/main 
* git log --online --decorate ----> Saber em qual parte do branch estou
* git branch  nome_da_nova_branch -----> Criar nova branch
* git checkout nome_da_branch  ------> Trocar a cabeza(main) para novo branch
* git merge testing   ------> juntar as diferentes branch