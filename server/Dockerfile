#  Dockerfile for Node Express Backend

FROM node:18.13.0

WORKDIR /server/index

COPY package*.json ./

RUN npm install --silent

COPY . .

EXPOSE 3000

CMD node index.js