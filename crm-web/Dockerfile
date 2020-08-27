FROM openjdk:13-alpine3.10

MAINTAINER Natascha "natascha.wernli@gibmit.ch"

EXPOSE 5051

WORKDIR /usr/local/bin

COPY ./httpServer.jar httpServer.jar

CMD ["java", "-jar", "httpServer.jar"]