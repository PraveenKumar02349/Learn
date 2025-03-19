Docker

Docker Container

Docker Image

Docker Registry

Docker Hub

docker pull name:version

docker run name:version

docker ps - to list running docker images

To Run by adding Name in docker image
docker run --name praveen-docker postgres

command prompt can be closed , still docker will run using
docker run -d postgres 

docker stop name or id

with port
docker run -d -p 4000:80 imageName

Docker registry - contains multiple images
Docker repository - cpntains versions of single image

Docker Image - using Dockerfile

![image](https://github.com/PraveenKumar02349/Learn/assets/83269149/4f608485-9738-4713-ab8f-5ed6609df79b)

docker build -t name:version . ---( . added to define location of dockerfile )

docker rmi imagename ( to remove image )

using BuildPacks 

![image](https://github.com/user-attachments/assets/166a05cb-6d7f-4d44-b47c-df185b683a94)

using Google Jib

![image](https://github.com/user-attachments/assets/30df2869-a1f7-4961-b58b-595b7282c033)

Google Jib can upload images to AWS, DockerHub too. check the commands in their github site.


![image](https://github.com/user-attachments/assets/43d86874-a3dd-4203-93d7-ccac2b7d25a7)


docker run -p 3306:3306 --name accountsdb -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=accountsdb -d mysql

