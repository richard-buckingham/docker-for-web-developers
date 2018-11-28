## Docker Machine Commands

docker-machine ls ## list all available docker machines. these are actually VirtualBox machines

docker-machine start [machine name]
docker-machine stop [machine name]
docker-machine env [machine name] # sets the docker machine the console is working with
docker-machine ip [machine name]
docker-machine status [machine name]

## Docker Client Image Commands

docker pull [image name]
docker images
docker rmi [image ID]

## Docker Client Container Commands

docker run [image name]		
# docker run -p 80:80 kitematic/hello-world-nginx 	forward from port 80 on the docker machine to port 80 in the container
# access the running container by navigating to http://192.168.99.100 in chrome

docker ps 					# see running containers
docker ps -a				# see all running containers
docker rm [container ID]


http://192.168.99.100