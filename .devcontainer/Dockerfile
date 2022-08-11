FROM node:lts-alpine3.16

WORKDIR /app

RUN apt update
RUN apt install -y git

COPY ~/.gitconfig .gitconfig
