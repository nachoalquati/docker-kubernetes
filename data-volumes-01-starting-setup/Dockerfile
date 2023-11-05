FROM node:14

WORKDIR /app

COPY package.json /app

RUN npm i

COPY . /app

ENV PORT 80   

EXPOSE $PORT


CMD ["npm" , "start"]