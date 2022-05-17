FROM node:14-alpine AS build
WORKDIR /usr/src/app
ADD node_modules.tar.gz /usr/src/app/
COPY . /usr/src/app/
EXPOSE 3001
ENTRYPOINT [ "npm" , "start" ]


