## How to get into a Docker container's shell?
  docker ps  
  docker exec -it <mycontainer> sh

## List all containers
  docker container ls  
  or docker ps

## Stop container
  docker container stop <contain_id>

## Show logs
  docker logs <container_id>

## Remove a container
  dcoker rm /redis
  
