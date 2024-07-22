[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/a4G18UV_)
# Punto 3: Documentacion del proyecto
## Descripcion y uso del proyecto
En este proyecto nos enfocamos en la definicion y funcionalidad de los Sistemas de Control de Version, los cuales son softwares en los que se almacenan proyectos y su historial, permitiendo manejar las versiones anteriores en caso de errores.
Al abarcar este tema nos encontramos con los repositorios, los cuales se manejan en programas como Git y Git Hub, hay repositorios locales y remotos, los cuales funcionan dependiendo de la necesidad del desarrollador, en estos se almacena el historial y todas las copias de los archivos. 
Este tipo de software es muy eficiente en proyectos de multiples desarrolladores, puesto que permite trabajo simultaneo y una mayor tranquilidad al experimentar nuevas herramientas y metodos puesto siempre hay una version anterior guardada, haciendo el trabajo mas eficaz y flexible 

## Como clonar y configurar nuestro proyecto 
Inicialmente debemos abrir Git Bash y ubicarnos en el directorio en el que deseamos clonar el proyecto, ahi utilizaremos un comando "git config --list" el cual nos enlistara las configuraciones actuales del proyecto, si deseamos editar alguna usaremos "git config -- global (lo que deseamos editar) "nuevo nombre"", un ejemplo:
- Para editar tu correo usarás "git config --global user.email "correo@gmail.com""
Despues de encargarnos de que nuestro proyecto este configurado correctamente, clonaremos el proyecto original, para esto usamos:
-"git clone "link repositorio""
Despues de realizar este paso podemos realizar los cambios necesarios y actualizarlos:
- "git add  "
- "git commit -m "comentario""
Tras esto enviaremos los cambios al repositorio remoto con el comando 
- "git push origin main/ master" (lo ideal es manejar nuestro proyecto en main)
