FROM mjgargani/puppeteer:trybe1.0

WORKDIR /usr/app

COPY package*.json ./

ADD node_modules.tar.gz ./

RUN npm install

COPY . .

CMD [ "npm" , "test" ]
