FROM node:13.12.0-alpine

RUN mkdir -p /app

WORKDIR /app

COPY package*.json /app

COPY . /app

RUN npm install

CMD ["npm","start"]

