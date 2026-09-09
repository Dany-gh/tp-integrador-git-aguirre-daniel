# Entrega del Trabajo Práctico Integrador

## Datos del participante

- Nombre y apellido: Daniel A. Aguirre
- Curso: introduccion a Git y GitHub para la Gestion de Proyectos Digitales.
- Fecha de entrega: 09/09/26

## Enlaces

- Repositorio de GitHub: https://github.com/Dany-gh/tp-integrador-git-aguirre-daniel.git
- Issue: https://github.com/Dany-gh/tp-integrador-git-aguirre-daniel/issues/1
- Pull request: 

## Comandos principales utilizados

Indicar los comandos utilizados durante el trabajo:

- git init
- git status
- git add .
- git commit
- git log --oneline
- git remote add origin
- git remote -v
- git push
- git branch
- git switch
- git merge
- git pull

## Descripción del proceso

Explicar en 5 a 8 líneas cómo se creó, versionó, publicó y documentó el proyecto.
-Abrimos Git Bash
-En el directorio que nos encontramos creamos con mkdir la carpeta tp-integrador-git-aguirre-daniel
 e ingresamos en ella con el comando cd.
-Creamos los archivos README.md y ENTREGA.md con el comando touch.
-Creamos la carpeta proyecto usando mkdir.
-Ingresamos a la carpeta proyecto con el comando cd.
-En esta carpeta creamos los archivos index.html y styles.css, usando el comando touch.
-Nos ubicamos en la carpeta tp-integrador-git-aguirre-daniel
-Abrimos los archivos README.md y ENTREGA.md con vscode y completamos con los contenidos obligatorios
 segun lo que piden en los puntos 8. y 9.
-Creamos el repositorio local usando
  git init
-Usamos git status para ver que tenemos.
-Le cambio nombre a la rama master creado por main usando
  git branch -m master main
-Veo en que rama estoy usando
  git branch
-Pasamos los archivos del area de trabajo al area stage con
  add .
-Pasamos del area stage al repositorio local usando commit
  git commit -m "mensaje"
-Vemos con status como estan las areas de trabajo y el area stage.
  git status
-Vemos como quedo el commit con
  git log o
  git log --online
-Ahora tenemos que publicar el repositorio local en remoto
-Creo en mi cuenta de GitHub el directorio o carpeta tp-integrador-git-aguirre-daniel
-En local configuro la direccion donde quiero publicar usando
  git remote add origin https://github.com/Dany-gh/tp-integrador-git-aguirre-daniel.git
-Revisamo si esta bien la url con
  git remote -v
-Luego publicamos en remoto con lo que tengo en local con
  git push -u origin main
-Creamos una ISSUE en remoto.
-Creamos una rama para cumplir con lo solicitado en la issue.
  git switch -c mejoras_solicitadas

## Dificultades encontradas

Ninguna

## Reflexión final

Se aprendio a usar Git de manera local y usar o como crear issue y pr en GitHub en el repositorio remoto.
En Git se aprendio a como crear o inicializar un repositorio local.
Como ver el estado de las areas de trabajo y stage.
Como pasar los archivos entre diferentes areas.
Pasar archivos del area stage al area de repositorio local, usando commit.
Crear cuenta en GitHub
Crear directorio en repositorio remoto.
Como configurar la direccion del repositorio remoto para usarla de manera local para hacer un push.
Tambien como crear ramas de manera local y pasar a esa rama creada.
Como crear issue en repositorio remoto
Como hacer pull request en repositorio remoto
Hacer un merge desde una rama a otra rama, todo en local.
Tambien poder hacer un pull, que es traer desde remoto a local.
Y hacer un clone deun repositorio remoto.

