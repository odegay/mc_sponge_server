FROM openjdk:16-jdk-alpine3.12

# RUN apt-get update && apt-get upgrade -y

# RUN apt-get install zip bash tar unzip screen wget -y

RUN apk update

RUN apk add zip bash tar unzip screen wget curl

RUN wget https://storage.googleapis.com/degayminecraft/server.zip

EXPOSE 26901