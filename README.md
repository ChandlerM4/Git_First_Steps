
## Git

### Funcionaldades y Comandos

* git --version: ver la version de Git que se tiene instalada.
* git config --global: la configuracion sera global y no por proyecto.
    * user.name "Name": configurar el nombre.
    * user.email + email: configurar email.
    * core.editor "code --wait": agregar VScode como editor de texto principal.
    * -e: saber si todo salio bien en VScode.
    * core.autocrlf true: salto de linea "true" en Windows y "input" en Mac.
    * -h: observar los comandos de Git admitidos.
    * git help: ayuda sobre los comandos.
* ls: observar las carpetas creadas.
* pwd: observar donde nos encuentramos.
* cd worlkspace/: usado para ingresar a cierta carpeta.
* cd ..: usado hace que se regrese a la carpeta anterior.
* mkdir + file name: crear carpeta nueva donde almacenar el codigo.
* git init: crear un repositorio en una carpeta y sus archivos estaran ocultos.
* ls -a: usado para mostrar archivos ocultos.
* git add: agrega los archivos seleccionados al "Stage" (para que este pendiente de los cambios).
* git add .: agrega todos los archivos al "Stage" (para que este pendiente de los cambios).
* git commit: se pasan los archivos seleccionados del "Stage" al "Commit".

| Computador | Stage | Commit | Server |

* git push: se pasan los archivos seleccionados del "Commit" al "Server".
* git .: se abriran las carpetas donde se encuentran en este momento en VScode.
* git status: observar el estado actual del repositorio.
* git commit -m "Comentario": crear commit.
* git rm + file name: eliminar un archivo.
* git restore + file name: restaurar un archivo eliminado.
* git mv + file name + new file name: cambiar de nombre un archivo.
* git status -s: ver estado actual especifico en el repositorio.
* git diff: para observar cambios realizados (salir con la tecla Q).
* git diff --stage: para observar cambios ya hechos en el stage.
* git log --online: muestra los comentarios de los cambios hechos en el commit en linea.
* got log: muestra los comentarios de los cambios hechos en el commit del mas reciente al mas antiguo.
* git branch: muestra en que rama estamos.
* git branch + nombreRama: crea una nueva rama.
* git checkout + nombreRama: para ingresar a dicha rama.
* git checkout -b + nombreRama: rama secundaria para la realizacion de cambios antes de pasar estos cambios a la rama principal.
* cat + file name: observar el contenido de un archivo.
