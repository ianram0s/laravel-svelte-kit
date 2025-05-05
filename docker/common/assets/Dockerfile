FROM node:18 AS build

WORKDIR /var/www

COPY package*.json ./
RUN npm install

COPY . .

RUN npm run build
