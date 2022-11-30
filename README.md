# **Documentación de la Practica 1**
## Vídeos Git pildorasinformaticas
He comenzado la practica de Entornos de desrrollo viendo los tres primeros video del canal de YouTube _pildorasinformaticas_.  
En estos tres videos, el youtuber explica los elementos básicos que se necesitan para empezar a realizar el trabajo:  
* Que es **Git** y para lo que nos puede se útil.
* Los comandos del git más importantes.
* Y como pasar todo lo que se ha hecho previamente a la plataforma **GitHub**.

## 1. Que es **Git** y para lo que nos puede se útil.
En este primer video se nos explica que la aplicación sirve como un instrumento de almacenamiento para guarda las diferentes versiones de un programa que estamos creando
y poder actualizarlo sin la necesidad de tener que guardar diferentes archivos completamente iguales sin que al final sepamos realmente qual es el archivo que realmente
funciona.

## 2. Los comandos del git más importantes.
En este video el youtuber nos enseña cuales son los comandos para GIT más importantes.  
Entre algunos está
```
git init
```
Este comando nos permite crear un nuevo repositorio en una carpeta, la cual tenemos que elegir antes de comenzar el proyecto.
```
git status
```
Nos permite comprobar cual es el estado del repositorio en el que estamos trabajando en caulquier momento.
```
git add archivo.txt
```
Nos permite añadir en el repositorio los archivos que se encuentran en el mismo escritorio en la que se localiza el repositorio. Este archivo puede ser cualquier tipo
de archivo: desde _.txt_ hasta _.css_.
```
git commit -m "Comentario asociado a este commit"
```
Este último comando es esencial para que el archivo que estamos modificando y que previamente hemos añadido en el área de ensayo se nos una en el historial de todos los 
cambios que hestamos haciendo en el repositorio. El texto localizado entre las comillas es el nombre que le ponemos al cambio.

## 3. Como pasar todo lo que se ha hecho previamente a la plataforma **GitHub**.
Lo primero que tenemos que hacer para llevar a cabo este paso es crear un usuario y contraseña en **GitHub** o, si ya tenemos uno, iniciar sesión en la página de github.  
Una vez que lo tengamos, Necesitamos crear un repositorio en el que necesitamos especificar:
* El nombre del repositorio.
* Poner una descripción, si es que la necesito o queremos.
* Hacerlo público o privado.
* Finalmente decidir si queremos poner algún otro aspecto como un README.md.
Una vez hecho ponemos el comando:
```
git remote add origin [url]
```
Con este comando lo que tratamos de hacer es adjuntar todos los archivos y el historial de cambios en nuestro repositorio de github.

## Mi experiencia con la práctica.
Los dos primeros vídeos no han sido mucho problema, ya que uno de ellos era un explicación de la aplicación y como descargarla; mientras que el otro eran comandos que
eran fáciles de aprender.  
El problema ha sido con el tercer video en el momento de pasarlo al GitHub. El problema era que, por más que actualizase la página web, no se me cargaban los cambios que
había realizado con la consola Git. Sin embargo, después de varios intentos y de buscar por internet que era exactamente lo que no me iba bien, la solución al problema
era tan f´cil como permitirle a Git realizar cambios en la página web desde la consola.
