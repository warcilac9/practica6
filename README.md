Wilbert Arcila Castellanos 
---
## Lenguajes Interpretados
Jonathan Mircha 

Materia en la que vemos como programar en diferentes lenguajes como JavaScript, markdown o css

## Sistemas Operativos 
Osiel Morales

En esta clase vemos como funcionan los sistemas operativos

## Composicion y diseño

Roberto Melo

En esta clase vemos sobre diseño y la composicion

## Diseño de videojuegos 
Hector Guerrero

En esta clase vemos como diseñar un videojuego para que cumpla con ciertos estándares.

## Proyecto de aplicacion
Sebastian Mejia 

En esta clase vemos como diseñar y producir una aplicación
---
Creando la versión v1.0.0
---
## Para inicializar un repositorio en Git:
Primero se abre la carpetacon el poyecto que queremos inicializar, luego abrimos la terminal y escribimos lo siguiente:

```bash
PS F:\Tercer Semestre\Lenguajes interpretados\práctica 6> git init
```
## Iniciar un repositorio en Github
Para esto deberemos de contar con una cuenta de Github, iniciamos en la pagina principal, le damos en nuestra foto de perfil, luego le damos en "Your repositories" y luego al botón verde que dice "new". De ahí le damos un nombre al repositorio y le decimos si queremos que sea público o privado. 

## Vincular repositorio local con repositorio remoto
En la terminal de nuestro proyecto escribiremos:

```bash
git add .
```
Esto hara que el repositorio lo guardemos localmente, luego le tendremos que hacer un commit de la siguiente forma:

```bash
git commit -m "nombre-del-commit"
git branch -M main
```
Luego lo siguiente es vincular los repositorios:

```bash
git remote add origin https://github.com/usuario/repositorio.git
```

Luego le tenemos que hacer un push a los cambios para subirlos al repositorio remoto, como sería el primero psh se escribiria así: 

```bash
git push -u origin main
```
ya los siguientes commits se escriben asi:

```bash
git push
```
## flujo básico
 El flujo básico se divide en cuatro etapas: modificado, staged, commit y remote:

 1- modificado: La carpeta local del proyecto de tu computadora
 1. staged: Tambien llamado indice y es donde se almacenn todos los cambios hechos al proyecto
 1. commit: aqui los cambios ya son parte del repositorio de git 
 1. remote: aqui los cambios ya se encuentran actualizados en el repositorio remoto
 