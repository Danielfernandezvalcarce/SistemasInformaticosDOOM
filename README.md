# ACTIVIDAD SISTEMAS INFORMATICOS DOCKER / DOOM

En la actividad planteada hoy, tendremos que ser capaces de jugar a la primera version de el videojuego DOOM, con una virtualizacion ligera de docker.

En un primer paso hemos de descargar el archivo de la siguiente pagina https://web.archive.org/web/20160310005603/https://gideonred.com/bins/dockerdoomd.tar.gz .

Nos vamos a nuestra carpeta de descargas de Ubuntu: 
<img src="https://i.gyazo.com/0bd0031f5925abebaf34dec8f583d5fc.png"> Al abrir la carpeta encontraremos un archivo en el que haremos click izquierdo y extraeremos ahi mismo.

Al extraerlo y entrar en la carpeta de la izquierda que se ha mostrado en la imagen anterior, encontraremos algo asi: 
<img src="https://i.gyazo.com/532d7b8f1dc0be93bb38020f25f6ecba.png"> al encontrarnos dentro de esa carpeta iniciaremos un terminal en la misma y correremos el comando ./dockerdoomd, como se muestra en la siguiente imagen.

<img src="https://i.gyazo.com/f50696390b84dd9c7adf867a6ad88c4c.png">

Una vez que el contenedor esta listo nos vamos a un navegador con conexion VNC e introducimos en el buscador: localhost:5900, por que como se ha indicado en la imagen anterior el contenedor esta desplegado en ese puerto.

<img src="https://i.gyazo.com/d7c11cc5b8a4b9181b08dfdef0cf738d.png">

Introducimos la contraseña que en este caso por defecto es 1234, y ya se nos despliega el contenedor con las imagenes cargadas, asi como se muestran en la ultima imagen, se puede jugar sin problema, aunque sea una virtualizacion ligera.
<img src="https://i.gyazo.com/6fc02f8ff368912f19c7496305c51927.png">