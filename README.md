## Images Commands

docker images

docker image ls

dcoker pull <image-name>

docker rmi <image-id>

docker build 


## Container Commands

docker ps     (list all running container)

docker ps -a  (list all running/stooped containers)

docker ps -aq  (List only ID)

docker rm <cont-id>

docker rm -f $(docker ps -aq)
