FROM node:14-alpine

WORKDIR /usr/app

COPY package*.json ./

ADD node_modules.tar.gz ./

RUN npm install

COPY . .

CMD [ "npm" , "start" ]

