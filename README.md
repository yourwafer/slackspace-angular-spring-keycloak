# Authentication with Spring Boot, AngularJS and Keycloak

## Requirement
### Tools

virtualbox

docker-machine

docker-compose

## Local development

cd keycloak

docker-machine create -d virtualbox --virtualbox-memory 4096 --virtualbox-cpu-count 4 default
 
eval $(docker-machine env default)

docker-compose up

## Run with standalone Tomcat

### Requirement:
    JDK1.8

To run the project with embedded Tomcat by maven:

    mvn spring-boot:run
  
Then navigate to [http://localhost:8000](http://localhost:8000) to see the application in action.
