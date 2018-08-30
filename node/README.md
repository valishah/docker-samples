### Node - Docker
To create a docker image 
`$ docker build -t node-js-app`

To run the docker image in container
`$ docker run -p 8080:8080 -d --name=node-app node-js-app`

To check the logs of running container 
`$ docker logs node-app`

To enter into the bash shell of running container
`$ docker exec -it node-app /bin/bash`

To find the present status of containers 
`$ docker ps`

To stop the container 
`$ docker stop node-app`

To remove the container 
`$ docker rm node-app`

To remove the image 
`$ docker rmi node-js-app`

**node-js-app** : image name
**node-app**    : container name
