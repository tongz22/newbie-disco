## Docker
- doker installs a linux virtula machine on the computer, the namespace allocate the prograss and cgroups allocate resources
- docker run = docker create + docer start
- docker start -a [container_id] -- show the detail
- docker start [container_id] -- no detail
- docker ps list all the image that are runing 
- docker ps --all all the image that runned
- docker system prune -- delete all the image and downloaded image
- docker logs [container_id] --list the detail from the container that has been run
- docker stop --shut down in 10 sec
- docker kill --shut down immediately 
- docker exec -it [container_id] -- run the command inside the container 
- -i get the STDIN -t good looking format
- docker run -it imagename sh

### add tag
docker build -t username/project_name:latest
docker run -it username/project_name

### docker compse
docker compose up --build
docker compose ps (need docker-compose to refer directry)

