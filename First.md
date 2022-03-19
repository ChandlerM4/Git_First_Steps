
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
* ls: observar las carpetas creadas.
* pwd: observar donde nos encuentramos.
* cd worlkspace/: usado para ingresar a cierta carpeta.
* cd ..: usado hace que se regrese a la carpeta anterior.
* mkdir + file name: crear carpeta nueva donde almacenar el codigo.
* git init: crear un repositorio en una carpeta y sus archivos estaran ocultos.
* ls -a: usado para mostrar archivos ocultos.
* git add: selecciona los archivos que se pasaran al "Stage".
* git commit: se pasan los archivos seleccionados del "Stage" al "Commit".

| Computador | Stage | Commit | Server |

* git push: se pasan los archivos seleccionados del "Commit" al "Server".
* git .: se abriran las carpetas donde se encuentran en este momento en VScode.
* git status: observar el estado actual del repositorio.
