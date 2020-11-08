## Requerimientos 

Docker, docker-compose, ab 

## Usos

Para controlar los contenedores se hace uso de los comando habituales asociados a docker-compose (up, stop, start, down) 
Debe ser ejecutado el comando de docker-compose en el directorio del proyecto: phpwebappv2

Partiendo del proyecto practica3_1, se realizan los siguientes pasos:

PASO 1

Lanzar 200 peticiones simultáneas durante 20 segundos a la dirección del balanceador usando los 4 frontales balanceados mediante el comando
   ab -c 200 -t 20 http://localhost:8081/
   
PASO 2
Lanzar 200 peticiones simultáneas durante 20 segundos a un único frontal a través de su puerto de acceso directo. El puerto aleatorio para acceso directo a cada frontal puede obtenerse con el comando ‘docker-compose ps‘
   ab -c 200 -t 20 http://localhost:PUERTOALEATORIO/
   
