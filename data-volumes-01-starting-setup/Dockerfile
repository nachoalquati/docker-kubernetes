FROM node:14

WORKDIR /app

COPY package.json /app

RUN npm i

COPY . /app

ARG DEFAULT_PORT=80 

ENV PORT $DEFAULT_PORT  

EXPOSE $PORT


CMD ["npm" , "start"]