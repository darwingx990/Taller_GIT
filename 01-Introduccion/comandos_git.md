# Comandos de git

## Comando para ver version  de git
- git -v
- git --version

## Comando para cambiar el nombre del archivo principal a main
- git branch -m main

## Comando para configuracion inicial de Git
- git config --global user.name "Darwing"
- git config --global user.email "Darwingx990@gmail.com"

## Comando para editar o ver la  configuracion de git

Para salir del edit Ctrl + o y ctrl x

- git config --global --edit
- git config --global --list

## Como iniciar git en un directorio

- git init

## Comando para saber el estado de nuestros archivos
- git status 

## Comando para listar las versiones de mi proyecto

- git log
- git log --oneline

## Comando para cambiar de version de commits y volver a una version anterior.

- git checkout <Id del commit o nombre de la rama>


## Pasos para crear una version de nuestro  codigo

1. Agregar todos los archivos al commit

- git add .
- git add *.js // para agregar solo archivos Javascript
- git add (fileName) // Para agregar un solo archivo. Ejm- git add index.js

2. Crear una nueva version. Tomar la foto del codigo (Crear una nueva version)

- git commit -m "Mensaje del commit"



