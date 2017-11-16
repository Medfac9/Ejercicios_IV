# Ejercicios del tema 4
## Ejercicio 1
Instala LXC en tu versión de Linux favorita. Normalmente la versión en desarrollo, disponible tanto en GitHub como en el sitio web está bastante más avanzada; para evitar problemas sobre todo con las herramientas que vamos a ver más adelante, conviene que te instales la última versión y si es posible una igual o mayor a la 1.0.

![Captura de pantalla1](https://imgur.com/yracerD.jpg)
![Captura de pantalla2](https://imgur.com/DNO9Icj.jpg)

## Ejercicio 2
Crear y ejecutar un contenedor basado en tu distribución y otro basado en otra distribución, tal como Fedora.

Aquí se puede observar un contenedor ejecutandose y bajado en mi distribución.  

![Captura de pantalla3](https://imgur.com/htToreD.jpg)

## Ejercicio 3
Instalar docker.

Para Mac, Docker posee un instalador propio (.dmg). Seguimos los pasos y ya lo tendremos instalado.

## Ejercicio 4
Instalar a partir de docker una imagen alternativa de Ubuntu y alguna adicional, por ejemplo de CentOS.

Para instalar Ubuntu se usaria `sudo docker run ubuntu`y para instalar CentOs `sudo docker run centos`.

Buscar e instalar una imagen que incluya MongoDB.

Para instalar una imagen que incluya MongoDB utilizamos `sudo docker run mongo`.

## Ejercicio 5
Crear un usuario propio e instalar nginx en el contenedor creado de esta forma.

![Captura de pantalla4](https://imgur.com/Noj9ivn.jpg)

E isntalamos nginx con `sudo apt install nginx`.

## Ejercicio 6
Crear a partir del contenedor anterior una imagen persistente con commit.

![Captura de pantalla5](https://imgur.com/q4N7Yvf.jpg)

![Captura de pantalla6](https://imgur.com/XTwqBgJ.jpg)

## Ejercicio 7
Crear un Dockerfile para el servicio web que se ha venido desarrollando en el proyecto de la asignatura.

Ejercicio resuleto para el hito 4.

## Ejercicio 8
Crear una imagen con las herramientas necesarias para el proyecto de la asignatura sobre un sistema operativo de tu elección.

Ejercicio resuleto para el hito 4.
