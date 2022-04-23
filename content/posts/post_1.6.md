---
title: "retroalimentación: Git"
date: 2022-04-07
description: 'Desde on boarding con Python hasta backend con javascript (NodeJS)'
---


# Git.

## comandos básicos en la Git Bash:

git init // Inicia un repositorio local
git add // Añade los ficheros al Index
git status // Comprueba el status del arbol de trabajo
git diff namefile// muestra los cambios en el archivo indicado
git stash // ignorar cambios y guarda como borrador con git stash pop y otras
git commit // Commit los cambios
git push // Enviar nuestros cambios al repositorio remoto
git pull // Descarga los últimos cambios del repositorio remoto
git clone // Clona, o realizar una copia desde el repositorio remoto al local
git log // Brinda información como autor correo y fecha Y el cómic o descripción del cambio que hizo el autor .
git branch // visualizar la rama en donde nos encontramos
git branch name// crea una nueva rama
get checkout name // cambia a esa rama
git blame file // visualizar quién edito el código.

### Match o fusión de ramas: Debemos estar ubicados en la rama principal : la primer rama guardara la información de la segunda rama
git marge name1 name 2 // fusiona ramas

### Crear 3ras ramas y moverte a ellas en 1 solo paso,con:
get checkout -b name
