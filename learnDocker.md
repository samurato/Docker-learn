# Learning Docker

## Docker Basics
* Starting a docker :-
	`docker run, docker start, docker pull`<br>
	`docker run -d -p 6000:6321`<br>
	`docker run` :- pull and start the image<br>
	`docker pull` :- Pull the image if it is not locally available and start <br>
	`-d` :- run in detatched mode
	`-p` :- buing the port hostport:dockerport
	
* Stopping a Docker :- `docker stop`
	``<br>
	
* ` ps` :- `docker ps -a` gives all container running or not. <br>
* `images`:- gives all the images that we have locally. <br>
*  `docker logs {Name or id of of the container}` :- outputs the log of the docker container eg:- `docker logs new-docker` or `docker logs asf112asf12re1`<br>
*  `docker stop ad123e121dd` :- Stops the specific docker container
*  `--name ` :- gives the name to the container eg:-  `docker run -d -p6001:6023 --name new-samrat redis:4.0` <br>
This runs the docker in detached mode exposing the hosts port 6001 to container 6023 with name new-samrat running redis 4.0

## Docker Troubleshooting
###Spawning Docker Shell 
`docker exec -it asd34123rarrasf /bin/bash` :- gives you a shell of the container.

Name or id both can be used to get the container's shell.




