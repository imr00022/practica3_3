# Simple deployment with an insecure webapp and a sql database

## Requerimientos 

Docker, docker-compose 


- Build and launch containers

```bash
$ make
```
- Monitor container resources

```bash
$ make mon
```
- Build containers images

```bash
$ make build
```
- Stop container and remove containers

```bash
$ make clean
```

## Options
- Database detailes, e.g. database name and user credentials can be customized in `docker-compose.yml` file
- Database must be initialized in url <http://localhost:8080/initdb.php>. It can take some time for mariadb container to initialize the database on the first launch
- `k8s` folder contains kubernetes config files for ingress loadbalancer and mariadb service deployment