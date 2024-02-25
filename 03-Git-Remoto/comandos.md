## Comando para colocar Git en la nube
- git remote add nombre_conexion url_conexion

## Comando para clonar o traer un repositorio de git 
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

## Comandos para traer informacion de la nube
- git pull 
- git pull nombre_conexion nombre_rama

## Comando para Configurar git para que ignore las diferencias de final de línea entre Windows y Unix.
- git config --global core.autocrlf false