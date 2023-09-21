FROM node

WORKDIR /data-volumes

COPY package.json .

EXPOSE 80

COPY . .

RUN npm install

# VOLUME ["/data-volumes/node_modules"]

VOLUME [ "/data-volumes/temp"]

CMD ["npm", "start"]