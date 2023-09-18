FROM node

WORKDIR /data-volumes

COPY package.json .

EXPOSE 80

COPY . .

RUN npm install

VOLUME [ "/data-volumes/feedback" ]

CMD ["node", "server.js"]