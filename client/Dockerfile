FROM node:10.15.0-alpine

ARG NODE_ENV="development"

WORKDIR /client

COPY package*.json ./

COPY . .



EXPOSE 5000

RUN npm install
CMD npm start
