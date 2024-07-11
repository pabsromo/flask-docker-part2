# flask-docker-part2
## Build and Run via Docker Compose
```
docker-compose up -d
```
## Check running Containers
```
docker-compose ps
```
or
```
docker ps -a
```
## Stop and Remove all Project Containers
```
docker-compose down
```
## Build and Run Containers to update state
```
docker-compose build
docker-compose up -d
```
## Resources
- https://www.docker.com/blog/containerized-python-development-part-2/