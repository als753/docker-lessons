dropwizard-helloworld
=====================

$ mvn clean package

$ java -jar target/dropwizard-helloworld-0.0.1.jar server config/dev_config.yml

Service endpoint: http://localhost:8080/hello-world

Admin: http://localhost:8081/

DOCKER

$ docker build -t <yourDockerHub>/dropwizard:<version> .

