FROM openjdk:13-alpine3.10

MAINTAINER Natascha "natascha.wernli@gibmit.ch"

EXPOSE 7070

WORKDIR /usr/local/bin

COPY ./target/maven.crm.web-0.0.1-SNAPSHOT.jar maven.crm.web-0.0.1-SNAPSHOT.jar

CMD ["java", "-jar", "maven.crm.web-0.0.1-SNAPSHOT.jar"]