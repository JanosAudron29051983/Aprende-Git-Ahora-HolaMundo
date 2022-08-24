# **Aprende Git HolaMundo**

## Configuración Inicial

```
git --version
git version 2.37.2.windows.2

git config --global user.name "Janos Audron"

git config --global user.email mmora29@gmail.com

git config --global core.editor "code --wait"

git config --global -e

git config --global core.autocrlf true
```

## Creación de carpeta e inicialización de repositorio
```
```

## Comandos
* Seleccionar archivos que queramos pasar a una etapa denominada Stage. No se ve reflejada en el repositorio.
```
git add
```
* Pasa los archivos de Stage a Commit y los borra de Stage.
```
git commit -m "Mensaje"
```
* Pasa los archivos de Commit a un servidor en la Nube. Ejemplos: GitHub, Git Server, etc.
```
git push
```
* Abre la carpeta en el programa de edición que hayamos configurado.
```
code .
```
* Muestra el estado del repositorio, si hay algún commit y muestra si los archivos tienen seguimiento de Git.
```
git status
```
* Solo el archivo, todos los archivos tipo txt o todos los archivos.
```
git add archivo.txt o *.txt o .
```
* Borra el archivo que le indiquemos sin hacer _"commit"._
```
git rm archivo1.txt
```
* Recuperar el archivo en Staged
```
git restore --staged archivo1.txt
```
* Recuperar el archivo
```
git restore archivo1.txt
```
* Cambiar nombre del archivo con commit
```
mv archivo1.txt archivo.txt
```
* Cambiar nombre del archivo sin commit
```
git mv archivo1.txt archivo.txt
```
* Ignorar archivos en Git
```
.gitignore
```
* Un mejor git status
```
git status -s
```
* Ver los cambios que he realizado en el archivo
```
git diff
```
Se sale con Q.

* Muestra los cambios Staged
```
git diff --staged
```
* Ver todo el historial de Git, ordenado con un hash
```
git log --oneline
```
* Saber en qué rama estoy?
```
git branch
```
* Crear una nueva rama 
```
git checkout -b ramab
```
* Saber contenido de los archivos en la rama seleccionada
```
cat -nombre_del_archivo
```
* Traer los datos de otra rama a la rama principal
```
git merge ramab
```
* Subir los cambios a GitHub
```
git push
```
* Luego de crear rama con "git checkout -b nombre_rama"
```
git push -u origin nombre_rama
```
Para subir en esa rama.

*Para más información puedes visitar el vídeo mostrado abajo:*

[Aprende GIT ahora! curso completo GRATIS desde cero](https://youtu.be/VdGzPZ31ts8)