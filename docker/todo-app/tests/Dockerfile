FROM node:14-alpine
WORKDIR /usr/src/app
ADD node_modules.tar.gz /usr/src/app/
COPY . /usr/src/app/
ENTRYPOINT [ "npm" , "start" ]
