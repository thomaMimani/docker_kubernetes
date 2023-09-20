FROM node

WORKDIR /data-volumes

COPY package.json .

EXPOSE 80

COPY . .

RUN npm install

CMD ["node", "server.js"]