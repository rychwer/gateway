FROM openjdk:8-jdk-alpine

RUN apk update && apk upgrade

RUN mkdir -p /usr/local/app

ADD  ms-config-server.jar /usr/local/app/

CMD java -jar /usr/local/app/ms-config-server.jar