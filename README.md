# **Documentación de la Practica 1**
## Vídeos Git pildorasinformaticas
He comenzado la practica de Entornos de desrrollo viendo los tres primeros video del canal de YouTube _pildorasinformaticas_.  
En estos tres videos, el youtuber explica los elementos básicos que se necesitan para empezar a realizar el trabajo:  
* Que es **Git** y para lo que nos puede se útil.
* Los comandos del git más importantes.
* Como pasar el repositorio local a la plataforma **GitHub**.

## 1. Que es **Git** y para lo que nos puede se útil.
En este primer video se nos explica que la aplicación sirve como un instrumento de almacenamiento para guardar las diferentes versiones de un programa que estamos creando.  
De este modo, podemos actualizarlo mientras el programa conserva estas versiones por si necesitamos volver atras.

## 2. Los comandos del git más importantes.
En este video, nos enseña cuales son los comandos para GIT más importantes.  
Entre los más importantes tenemos:
```
git init
```
Nos permite crear un nuevo repositorio en una carpeta, la cual tenemos que elegir antes de comenzar el proyecto.
```
git status
```
Nos permite comprobar cual es el estado del repositorio en el que estamos trabajando en cualquier momento.
```
git add archivo.txt
```
Nos permite añadir en el área de ensayo los archivos que se encuentran en nuestra carpeta de trabajo, antes de añadirlo en el repositorio. Este archivo puede ser de cualquier tipo, desde _.txt_ hasta _.css_.
```
git commit -m "Comentario asociado a este commit"
```
Este último comando es esencial. para que el archivo que estamos modificando y, que previamente hemos añadido en el área de ensayo, se añada al repositorio. De este modo, se añade una nueva versión al historial de versiones de nuestro archivo. El texto entre comillas es el nombre que le asignamos a esta versió y que nos permite ver que lo diferencia de la versión anterior.

## 3. Como pasar el repositorio local a la plataforma **GitHub**.
Lo primero que tenemos que hacer es crear un usuario y contraseña en **GitHub** o, si ya tenemos uno, iniciar sesión.  
Una vez que lo tengamos, necesitamos crear un repositorio en el que especificaremos:
* El nombre.
* Poner una descripción, es opcional.
* Hacerlo público o privado.
* Decidir si queremos poner algún otro aspecto como añadir un README.md.
Una vez creado el repositorio en GitHub ponemos el comando:
```
git remote add origin [url]
```
Con este comando lo que hacemos es subir todos los archivos y el historial de cambios de nuestro repositorio local al repositorio de GitHub.

## Mi experiencia con la práctica.
Los dos primeros vídeos no han sido mucho problema, ya que uno de ellos era un explicación de la aplicación y como descargarla; mientras que el otro eran comandos que
eran fáciles de aprender.  
El problema ha sido con el tercer video en el momento de pasarlo al GitHub. El problema era que, por más que actualizase la página web, no se me cargaban los cambios que
había realizado con la consola Git. Sin embargo, después de varios intentos y de buscar por internet que era exactamente lo que no me iba bien, el problema era que no habia autorizado a la consola de Git a realizar cambios en GitHub.
