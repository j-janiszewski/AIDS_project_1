FROM node:18-alpine

WORKDIR /backend

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD ["node", "app.js"]