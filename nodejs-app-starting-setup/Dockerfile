FROM node

WORKDIR /app

COPY . /app

RUN npm install

EXPOSE 80

ENTRYPOINT [ "node", "server.js" ]
