FROM node:14.21.3-slim

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 3000

CMD ["node", "server.js"]