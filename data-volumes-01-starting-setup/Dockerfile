FROM node:14

WORKDIR /app

COPY package.json /app

RUN npm i

COPY . /app

EXPOSE 80

VOLUME [ "/app/feedback" ]

CMD ["node" , "server.js"]