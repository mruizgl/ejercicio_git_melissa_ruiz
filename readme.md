<div>

# Práctica de Git
1. Creo repositorio en mi cuenta de GitHub con el nombre ejercicio_git_melissa_ruiz: https://github.com/mruizgl/ejercicio_git_melissa_ruiz.git
2. Realizamos la clonación usando 
```
git clone https://github.com/mruizgl/ejercicio_git_melissa_ruiz.git 
Clonando en 'ejercicio_git_melissa_ruiz'...
warning: Pareces haber clonado un repositorio sin contenido.
```

3. Me ubico en el directorio del repositorio que hemos clonado y añado el archivo readme.txt al repositorio y realizo el primero commit 
```
cd ejercicio_git_melissa_ruiz/
dam@a108pc07:~/ejercicio_git_melissa_ruiz$ git add readme.md
dam@a108pc07:~/ejercicio_git_melissa_ruiz$ git commit -m "Commit inicial"
[main (commit-raíz) bd2b571] Commit inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md
```
4. Crear una rama con nombre develop.
```
dam@a108pc07:~/ejercicio_git_melissa_ruiz$ git checkout -b dev
Cambiado a nueva rama 'dev'
```
5. Lista las ramas actuales.
```dam@a108pc07:~/ejercicio_git_melissa_ruiz$ git branch --all
* dev
  main
```
6. Moverse a la rama y crear el fichero: hola.html. y añadir el contenido: melissa_ruiz

```
dam@a108pc07:~/ejercicio_git_melissa_ruiz$ cat > hola.html
melissa_ruiz 
```html
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
<head>
<title>Hola </title>
</head>
<body>
<h1 align="center" >Hola soy un título </h1>
<hr>
<p> Hola soy el alumno nombre_alumno </p>
</body>
</html>
```
7. Moverse a la rama principal y crear el fichero adios.html 
```
dam@a108pc07:~/ejercicio_git_melissa_ruiz$ git checkout main
Cambiado a rama 'main'
Tu rama está basada en 'origin/main', pero upstream ha desaparecido.
  (usa "git branch --unset-upstream" para arreglar)
dam@a108pc07:~/ejercicio_git_melissa_ruiz$ git branch --all
  dev
* main
```
8. 
```
dam@a108pc07:~/ejercicio_git_melissa_ruiz$ cat > adios.html
melissa_ruiz
dam@a108pc07:~/ejercicio_git_melissa_ruiz$ nano adios.html
dam@a108pc07:~/ejercicio_git_melissa_ruiz$ git add .
dam@a108pc07:~/ejercicio_git_melissa_ruiz$ git commit -m "Añadimos archivos hola y adios"
[main f1216b5] Añadimos archivos hola y adios
 2 files changed, 29 insertions(+)
 create mode 100644 adios.html
 create mode 100644 hola.html
```



</div>