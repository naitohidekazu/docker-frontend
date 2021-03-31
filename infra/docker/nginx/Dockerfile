FROM node:14.15.0-alpine

WORKDIR /src/app

RUN apk update && \
    npm install -g npm @vue/cli && \
    yarn install

ENV HOST 0.0.0.0
