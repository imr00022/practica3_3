# Simple deployment with an insecure webapp and a sql database

## Requerimientos 

Docker, docker-compose 

## Usos

Para controlar los contenedores se hace uso de los comando habituales asociados a docker-compose (up, stop, start, down) 
Debe ser ejecutado el comando de docker-compose en el directorio del proyecto: phpwebappv2

PASO 1
- Clonar el proyecto practica3_1 en tu máquina local

PASO 2
- Inicializar servicios, lanzado el comando docker-compose up dentro la carpeta del proyecto.

PASO 3
- Inicializar la base de datos atacando la URL correspondiente ( ver opciones )

PASO 4

- Se realizan varias consultas vía navegador 

PASO 5
- Visualizar el log para ver que se realiza correctamente el balanceo, con los comandos docker-compose logs y docker stats


## Opciones

- Los usuarios de la base de datos puede ser modificados en el fichero 'docker-compose.yml'
- Para iniciar la base de datos se debe realizar mediante la siguiente url: http://localhost:8081/initdb.php 
