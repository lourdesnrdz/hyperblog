# Hyperblog
Un blog increíble para el curso de Git y Github de Platzi

En este curso vi cómo utilzar los comandos de Git y la plataforma de Github. También aprendí las buenas prácticas al trabajar con los repositorios y de manera colaborativa con otras personas en un proyecto.

Asimismo, aprendí cómo configurar las llaves SSH para crear, crear tags, manejo de branches, colaboraciones, fork de un proyecto (contribuir por open source), manejar errores, crear `Readme.md`, hosting con [Github Pages](https://lourdesnrdz.github.io/hyperblog/) y más.

<!-- [Hyperblog](https://lourdesnrdz.github.io/hyperblog/blogpost.html) -->

## Comandos 

| Comando | Descripción |
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
| git branch -a | Muestra todas las ramas tanto locales como remotas |
