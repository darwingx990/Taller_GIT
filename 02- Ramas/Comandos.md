## Comandos para listar las ramas de mi repositorio

-git branch
git branch -v

## Comandos pars crezr una rama

- git branch nombre_rama

## Comando para  cambiar de ramas
- git chrckout nombre_rama
- git switch nombre_rama
-git checkout -bnombre_rama y hace el cambio

## Comando para eliminar una rama

- git branch -d nombre_rama

## Comando para cambiar el nombre de una rama

- git branch -m nuevo_nombre

## Comando para guardar carpetas vacias en Git
Se crea la carpeta y dentro de ella se crea un archivo llamado: 
.gitkeep

## Crear nuestro propios comandos
En la parte del lg va el nombre que le queremos poner y en comillas vas el comando que quiero que se ejecute con ese alias

- git config --global alias.lg "log --oneline"


## Comando para eliminar un archivo de Git
Se ubica en la carpeta donde esta el archivo con cd.
si no se pone el --cached, el archivo se borrara tambien del local.

- <git rm --cached ><nombre_archivo>

## Comando para clonar o traer un repositorio dd git 
- git clone URL_Conexion

## Comando para listar las conexiones remotas
- git remote -v

## Comando para eliminar una conexion remota
- git remote remove nombre-conexion

## Comando para enviar informacion a la nube
- git push // Envia informacion a la rama actual
- git push nombre_conexion nombre_rama
- git push -u nombre_conexion nombre_rama //Si no existe la crea
- git push --all // Envia informacion a todas las rama

## Comandos para traes informacion de la nube
