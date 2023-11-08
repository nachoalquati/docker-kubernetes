FROM node:14.5

WORKDIR /app

COPY package.json /app

RUN npm i

COPY . /app

# ARG API=http://backend/

# ENV API $API

CMD [ "npm" , "start" ]