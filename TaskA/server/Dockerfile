FROM node:latest

WORKDIR /usr/src/app

RUN npm install

COPY . .

EXPOSE 5000
CMD ["node", "server.js"]