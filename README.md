# How to run application from Docker  

1. You need to run sonatype/nexus3 image using docker-compose.yml file.
Open cmd and navigate to DockerConvertator/src/main/resources directory. Then run command:  
```docker-compose up```  
Wait until the note "Started Sonatype Nexus OSS 3.22.0-02" appears.
2. Now you need to pull image from docker and run it.
Run this command to pull latest image:  
```docker pull localhost:8123/repository/ivansdockerrepo/converter```  
And then this to run the image:  
```docker run localhost:8123/repository/ivansdockerrepo/converter``` 
