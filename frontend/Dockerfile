FROM node:16.14.2

COPY . /frontend

WORKDIR /frontend

RUN npm i
RUN npm run build
RUN npm install -g serve