Poner nombre global del git ->
git config --global user.name Abelmp17

Poner email global del Git ->
git config --global user.email abelmp890@gmail.com

Editar la configuracion del git desde esl editor de codigo ->
code ~/.gitconfig 

Iniciamos el git ->
git init 

Estado del git ->
git status

Añadimos fichero al git para que esté en seguimiento ->
git add <fichero>

Miras el estado de los archivos del git ->
git status -s

Haces un commit de los archivos añadidos ->
git commit -m "<descripcionDelCommit>"

Nos conectamos al repositorio ->
git remote add <nombreRaíz> https://github.com/nombreUsuario/nombreRepositorio.git

Obtenemos los archivos subidos al repositorio ->
git pull

Subimos los commits realizados ->
git push <nombreRaíz> <master/main>
  
Vemos los commits del repositorio ->
git log
