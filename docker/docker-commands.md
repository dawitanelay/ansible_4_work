1 create and start container
 ```sh
docker-compose up
```
2 create and start container on detach mode
```sh
docker-compose up -d 
```
3 create and start speacific service and it's container
```sh
docker-compose up -d <service>
```
4 List containers 
```sh
docker-compose ps <service>
```
5 stop and  remove container 
```sh
docker-compose down <service>
```
6 list images (running service only)
```sh
docker-compose images
```
7 view logs 
```sh
docker-compose rm <service>
```
8 execute a command in a running container 
```sh
docker-compose exec <service> <command>
```
9 execute command in detach mode
```sh
docker-compose exec -d <service> <command>
```
10 scale containers for a service 
```sh
docker-compose up -d --scale <service>=<Num>
```
11 using diffrent file 
```sh
docker-compose -f <composefile> up -d 
```
