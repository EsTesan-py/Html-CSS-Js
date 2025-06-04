# Git Comandos
## ¿Qué es Git?
Git es un sistema de control de versiones distribuido. Es una herramienta de software distribuida para rastrear cambios en el código. Git permite trabajar en equipo, compartir el trabajo y mantener versiones de los archivos.
## Algunos comandos básicos
### Crear un directorio
Crearemos principalmente un directorio para almacenar nuestro proyecto
```bash
mkdir nombre-directorio
```
### Crear un archivo
Luego creamos un archivo con la extensión que queramos. Por ejemplo, si queremos crear un archivo de texto, podemos usar la extensión .txt
```bash
touch nombre-archivo.txt
touch nombre-archivo.md
touch nombre-archivo.html
```
### Copiar un archivo
Copiamos un archivo a otro
```bash
cp nombre-archivo.txt nombre-archivo-copia.txt
cp nombre-archivo.md nombre-archivo-copia.md
cp nombre-archivo.html nombre-archivo-copia.html
```
### Mover un archivo
Movemos un archivo a otro
```bash
mv nombre-archivo.txt nombre-archivo-copia.txt
mv nombre-archivo.md nombre-archivo-copia.md
mv nombre-archivo.html nombre-archivo-copia.html
```
### Eliminar un archivo
Eliminamos un archivo
```bash
rm nombre-archivo.txt
rm nombre-archivo.md
rm nombre-archivo.html
```
### Listar archivos
Listamos los archivos que tenemos en el directorio
```bash
ls
```
### Cambiar el directorio
Cambiamos el directorio que estamos en
```bash
cd directorio
```
## Ahora comandos con Git
### Creacion de cuenta de Git
Creamos una cuenta de Git
```bash
git config --global user.name "nombre-usuario"
git config --global user.email "correo-usuario@dominio.com"
```
### Crear un repositorio
Creamos un repositorio en el directorio que estamos
```bash
git init
```
### Añadir archivos
Añadimos archivos a la zona de staging, podemos añadir todos los archivos con git add . o solo los archivos que queramos
```bash
git add nombre-archivo.txt
git add nombre-archivo.md
git add nombre-archivo.html
```
### Revisamos el estado de los archivos en el staging
Revisamos los cambios que hemos hecho durante el tiempo de trabajo
```bash
git status
```
### Commitear cambios
Commiteamos los cambios que hemos hecho
```bash
git commit -m "mensaje"
```
### Creamos el repositorio remoto
Creamos un repositorio remoto en GitHub, debemos hacerlo en la pagina de GitHub. Luego copiamos el link que aparece en la parte superior de la página.
```bash
git remote add origin https://github.com/usuario/carpeta-ejemplo.git
```
### Pushear cambios
Subimos los cambios al repositorio
```bash
git push
```
## Revisamos los cambios en el repositorio
```bash
git fetch
```
### Pullear cambios
Extraemos los cambios del repositorio
```bash
git pull
```
