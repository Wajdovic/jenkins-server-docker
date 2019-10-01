# jenkins-server-with-docker-client

A jenkins server with a docker client preinstalled

## How to use:

`docker-compose up` (to run the service, you can add -d for detach mode).

`docker-compose down` (to kill the service)


Jenkins will be running on port 8080.

At first connexion you will be asked to enter a token to unblock jenkins, you will find find it in the logs of jenkins container :

    docker ps ( get the container id)
    
    docker logs <container-id>

**NB:**
If you are using windows, docker client will not work :) 


