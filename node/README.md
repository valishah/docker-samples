### Node - Docker
To create a docker image </br>
`$ docker build -t node-js-app`

To run the docker image in container</br>
`$ docker run -p 8080:8080 -d --name=node-app node-js-app`

To check the logs of running container </br>
`$ docker logs node-app`

To enter into the bash shell of running container</br>
`$ docker exec -it node-app /bin/bash`

To find the present status of containers </br>
`$ docker ps`

To stop the container </br>
`$ docker stop node-app`

To remove the container </br>
`$ docker rm node-app`

To remove the image </br>
`$ docker rmi node-js-app`

**node-js-app** : image name</br>
**node-app**    : container name
