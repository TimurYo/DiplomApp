FROM node:latest

WORKDIR /home/node/app

COPY package.json package.json
COPY package-lock.json package-lock.json

RUN npm install

COPY . .

CMD ["node", "server.js"]
EXPOSE 9999