FROM node:10.13

RUN apt-get -y update
RUN apt-get -y install git wget sudo
RUN npm -g config set user root

WORKDIR /usr/src/app
RUN npm install -g grunt-cli

COPY . .

EXPOSE 8282
