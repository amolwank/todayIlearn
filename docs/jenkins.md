# Jenkins Learn

## Jenkins installation using docker

###Create a folder as volume to attach to jenkins like 
/home/awankhede/developement/docker/jenkins_home/
>sudo chown -R 1000:1000 jenkins_home/

>docker run -p 8080:8080 -p 50000:50000 --restart always -v /home/awankhede/developement/docker/jenkins_home/:/var/jenkins_home jenkins/jenkins:lts-jdk11

>localhost:8080/restart to restart jennkins.
