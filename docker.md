Docker

Docker Container

Docker Image

Docker Registry

Docker Hub

docker pull name:version

docker run name:version

docker ps - to list running docker images

To Eun by adding Name in docker image
docker run --name praveen-docker postgres

command prompt can be closed , still docker will run using
docker run -d postgres 

docker stop name or id

with port
docker run -d -p 4000:80 imageName

Docker registry - contains multiple images
Docker repository - cpntains versions of single image

Docker Image - using Dockerfile

![image](https://github.com/PraveenKumar02349/Learn/assets/83269149/88fca770-8bc6-4a9f-b46c-a05c8ea23e79)

docker build -t name:version . ---( . added to define location of dockerfile )


