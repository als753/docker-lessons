FROM java:8-jre
MAINTAINER Amanda Snyder "asnyder@thoughtworks.com"

COPY target/dropwizard-helloworld-0.0.1.jar /opt/dropwizard/

COPY config/dev_config.yml /opt/dropwizard/

EXPOSE 8080

WORKDIR /opt/dropwizard

CMD ["java", "-jar", "-Done-jar.silent=true", "dropwizard-helloworld-0.0.1.jar", "server", "dev_config.yml"]
