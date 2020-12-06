FROM node:14.5.0-alpine


RUN apt-get update &&\
    apt-get install install -y git

WORKDIR /usr/src/server

RUN git clone https://github.com/nestjs/typescript-starter.git .

RUN npm install