# tarea_repaso_nov24
Repaso T1 EEDD 
Los pasos realizados han sido los siguientes:

1. He creado el repositorio remoto en GitHub
2. Como tenía cerrada la consola Git Bash, he tenido que hacer esto:
    2.1 Ir a la ruta del directorio local donde voy a clonar el repositorio de GitHub.
    2.2 He iniciado Git (el programa que controla versiones de archivos). Comando = git init
    2.3 Para poder clonar el repositorio y que no me pida la clave SSH cada vez que decida 
    comunicarme con Git, he levantado el agente SSH y añadido mi clave privada, para lo que
    he tenido que introducir la contraseña de la clave.
3. He clonado el repositorio de GitHub. Comando = git clone + dirección https del directorio 
    de GitHub.

4. He creado la estructura de archivos y carpetas del enunciado desde la consola Git Bash. 
    Para ello:
    4.1 Comando creación de carpetas = mkdir -p app configurations local_config manuals media
    4.2 Creación de los ficheros correspondientes en cada carpeta: 
    touch app/main.js manuals/instrucciones.pdf media/banner.jpg configurations/settings.json
    local_config/configuracion_local.iniciado

5. He sincronizado el directorio local con GitHub en diferentes ocasiones:
    5.1 Cuando he creado las estructuras de carpetas
    5.2 Cuando he modificado el archivo settings.json
    5.3 Cuando he vuelto a modificar el archivo settings.json

    Para todo lo realizado en el punto 5, los comandos han sido los siguientes:

    git add . (para preparar todo el contenido del directorio local del que quiero establecer
    un punto de control y sincronizar con el repositorio remoto de GitHub).

    git commit - m " " (para establecer en local un punto de control con la descripción de los 
    cambios realizados hasta el momento, y que quiero que consten en GitHUb).

    git push (para enviar a GitHub todos los archivos y commits. Es decir, el repositorio local
    con los últimos cambios y los comentarios de cada commit).

    

