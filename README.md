docker pull IMAGE-NAME
docker images (to see the images in folder)
docker run IMAGE-NAME
docker run -it IMAGE-NAME (with interactive input)
docker ps -a (To see status)
docker start CONT_NAME or CONT_ID


### To remove image
docker rmi IMAGE_ID
(First you have to remove container if image is in use)
docker rm CONT_ID

docker pull mysql:8.0
