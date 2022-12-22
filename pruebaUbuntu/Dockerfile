#Base Imagen Ubuntu:14.04
FROM ubuntu:14.04

#Creamos una carpeta en el contenedor con el nombre "myvolC"
RUN mkdir /home/myvolC

#Definimos deirectorio de trabajo
WORKDIR /home/myvolC

#Almacena el texto "hello world" en el archvio "greeting" de la carpeta "myvolC"
RUN echo "hello world" > greeting

#Creamos enlace entre carpeta anfitrio y carpeta contenedor 
VOLUME /home/myvolC
