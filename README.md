![](https://github.com/cleversonledur/jenkins-docker-compose/blob/master/images/jenkins.png =100x20)
# Jenkins Docker Compose
A simple docker-compose project for starting up a Jenkins instance.

You will need docker-compose installed in your system. Check out how to do this [here](https://docs.docker.com/compose/install/)


To start, just run the following command on this repository root directory:

```
docker-compose run 
```

Then, access Jenkins using the browser.

- http://localhost:8080

P.s: You will have to check jenkins logs in order to get the initial password. Use docker logs (container Id) for this.
