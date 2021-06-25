# Hyperblog
An incredible blog for the Git and Github course from Platzi

## Table of contents

* [General info](#general-info) 
* [Technologies](#technologies) 
* [Commands](#commands)

<!-- Un blog increíble para el curso de Git y Github de Platzi -->

<!-- En este curso vi cómo utilzar los comandos de Git y la plataforma de Github. También aprendí las buenas prácticas al trabajar con los repositorios y de manera colaborativa con otras personas en un proyecto.

Asimismo, aprendí cómo configurar las llaves SSH para crear, crear tags, manejo de branches, colaboraciones, fork de un proyecto (contribuir por open source), manejar errores, crear `Readme.md`, hosting con [Github Pages](https://lourdesnrdz.github.io/hyperblog/) y más. -->

## General info

In this course I learned how to use Git commands and the Github platform. Also, I learned good practices when working with repositories and collaborating with other people on a project.

I also learned how to manage SSH keys, to create tags, manage branches, fork a project (open source contributions), manage errors, create a `Readme.md`, hosting with Github Pages and more.

Throught the course we developed a hyperblog, and used the git commands to manage the proyect through the terminal. We used the Hyperblog to create scenarios and cases to learn how to resolve errors and conflicts, what to do when you make unintentional commits, when you break the project, etc.

[Example Github Pages](https://lourdesnrdz.github.io/hyperblog/index.html)

[Hyperblog](https://lourdesnrdz.github.io/hyperblog/blogpost.html)

## Technologies

On this course I used the following development technologies:
 - Visual Studio Code
 - Git
 - Github
 - HTML and CSS

## Commands 
These are the commands that we learned throughout the course.

| Command | Description |
|---------|-------------|
| git init | Create repository |
| git add {nombrearchivo} o {.} | Staging changes |
| git commit | Save changes in repository |
| git log | Show history of commits |
| git branch {branch_name} | Create a new branch |
| git checkout -b {branch_name} | Create and move to a new branch |
| git checkout {branch_name} | Move to a branch |
| git merge {branch_name} | Merge one branch with another one |
| git branch | Show existing branches |
| git remote add origin {url} | Save URL of Github repository |
| git remote -v | Show remote conexions of local repository |
| git pull origin {branch_name} | Bring version from remote repository to local repository |
| git push origin master | Save changes on remote repository on GitHub |
| git push origin {branch_name} | Save changes on remote repository |
| git show | Shows the last changes made |
| git status | Shows the state of all our files and folders |
| git remote add upstream {url} | Creates an aditional remote repositry |
| git pull upstream main | Brings changes from main. Pull from new origin. |
| git rebase main | Merge feature branch with main branch |
| git rebase main | Merge feature branch with main branch |
| git stash | Returns to last changes |
| git stash pop | Retrieve the latest changes from the stash to your staging area |
| git stash drop | Deletes last changes from stash |
| git clean --dry-run | Shows what files are going to be deleted |
| git clean -f | Deletes listed files |
| git cherry-pick {commit} | Brings commit from another branch to main |
| git commit --amend | Adds changes to previous commit |
| git reflog show --all | Get a reflog of all your HEAD references |
| git reset --soft {HEAD} | Reset HEAD pointer, keeps what's on staging |
| git reset --hard {HEAD} | Reset HEAD pointer, deletes what's on staging |
| git grep {word} | Search for word on project |
| git grep -n {word} | Returns on what lines the word appears |
| git grep 'c {word} | Return number of times the word appears and on what file |
| git log-S {word} | Shows commits that contain the word |
| git shortlog | Shows a log for each contribuitor and what have they done |
| git shortlog -sn | Shows the number of commits each team member has made |
| git shortlog -sn --all | Shows number of commits of each memeber including deleted commits |
| git shortlog -sn --all --no-merge | Shows number of commits of each memeber not including deleted commits and merges |
| git blame {file} o git blame -c {file} | Shows who has done what line by line |
| git blame {file} -L{start},{fin} | Shows who has done what line by line in a range of lines (example: -L35,50) |
| git {command} --help | Shows how the command works |
| git branch -r | Shows all remote branches |
| git branch -a | Shows all local and remote branches |

<!-- | Command | Description |
|---------|-------------|
| git init | Crear repositorio |
| git add {nombrearchivo} o {.} | Staging de los cambios |
| git commit | Guarda los cambios de manera definitiva en el repositorio |
| git log | Ver historial de commits |
| git branch {branch_name} | Crea una nueva rama |
| git checkout -b {branch_name} | Crea una nueva rama y nos posiciona en ella |
| git checkout {branch_name} | Nos posiciona en la rama seleccionada |
| git merge {branch_name} | Fusiona una rama con otra |
| git branch | Ver las ramas creadas |
| git remote add origin {url} | Guardar la URL del repositorio de GitHub |
| git remote -v | Visualizar las conexiones remotas del repositorio local |
| git pull origin {branch_name} | Traer la versión del repositorio remoto |
| git push origin master | Guardar los cambios de nuestro repositorio remoto en GitHub|
| git push origin {branch_name} | Guarda los cambios en el repositorio remoto |
| git show | Muestra los últimos cambios que se hicieron |
| git status | Permite ver el estado de todos nuestros archivos y carpetas |
| git remote add upstream {url} | Crea un repositorio remoto adicional |
| git pull upstream main | Trae los cambios de main. Hacer pull desde el nuevo origen. |
| git rebase main | Fusiona la rama feature con la rama main |
| git rebase main | Fusiona la rama feature con la rama main |
| git stash | Regresar el cambio anterior que hicimos |
| git stash pop | Recuperar los últimos cambios desde el stash a tu staging area |
| git stash drop | Eliminar los últimos cambios desde el stash |
| git clean --dry-run | Muestra qué archivos vamos a borrar |
| git clean -f | Borra los archivos listados |
| git cherry-pick {commit} | Traer commit de otra rama a master |
| git commit --amend | Agrega los cambios al commit anterior |
| git reflog show --all | Obtener un reflog de todas las referencias de tu HEAD |
| git reset --soft {HEAD} | Restablece el apuntador HEAD, mentiene lo que hay en staging |
| git reset --hard {HEAD} | Restablece el apuntador HEAD, borra todo lo que hay en staging |
| git grep {word} | Busca en todo el proyecto donde está la palabra |
| git grep -n {word} | Regresa en qué líneas está l apalabra |
| git grep 'c {word} | Regresa cuántas veces se repite la palabra y en qué archivo |
| git log-S {word} | Muestra los commits que contienen la palabra |
| git shortlog | Muestra un log por persona de lo que ha hecho cada miembro |
| git shortlog -sn | Muestra cuantos commit han hecho cada miembros del equipo |
| git shortlog -sn --all | Muestra cuantos commits ha hecho cada miembro incluyendo commits eliminados |
| git shortlog -sn --all --no-merge | Muestra cuantos commit ha hecho cada miembrosin incluir los eliminados ni los merges |
| git blame {file} o git blame -c {file} | Muestra quien hizo cada cosa linea por linea |
| git blame {file} -L{start},{fin} | Muestra quien hizo cada cosa linea por linea en un rango de líneas (ejemplo: -L35,50) |
| git {command} --help | Muestra como funciona el comando |
| git branch -r | Muestra todas las ramas remotas |
| git branch -a | Muestra todas las ramas tanto locales como remotas | -->
