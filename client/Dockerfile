
FROM node:18.13.0

WORKDIR /client/src/app

COPY package*.json ./


RUN npm install --silent

COPY . .

EXPOSE 3000

CMD ["yarn","start"]