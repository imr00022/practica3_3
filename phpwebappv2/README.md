
## Requerimientos 

Docker

## Usos

Para controlar los contenedores se hace uso de los comando habituales asociados a docker-compose (up, stop, start, down) 
Debe ser ejecutado el comando de docker-compose en el directorio del proyecto: phpwebappv2


$ docker-compose up -d

Acceso al balanceador haproxy GUI en el puerto 8081, por ejemplo: http://localhost:8081/stats

Acceso a los frontales web, mediante la URL: http://localhost:8081/


Reconstruir imagenes de los contenedores:

$ docker-compose build
Para y eliminar las imágenes:
$ docker-compose down

Referencias consultadas:

https://clouding.io/hc/es/articles/360010289000-Balancear-servicio-web-con-HAProxy-en-Ubuntu-18-04 

https://servernotfound.es/haproxy-las-4-secciones-principales/

