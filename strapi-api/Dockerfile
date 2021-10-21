from node:14

#https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

RUN npm run build

EXPOSE 1337

CMD [ "npm", "run", "start" ]