FROM node:16-alpine

WORKDIR /usr/src/app

COPY package*.json ./

COPY . .

RUN npm install -g npm@7.24.2 npm-check-updates
RUN npm install


EXPOSE 3000

CMD [ "node", "server.js" ]
