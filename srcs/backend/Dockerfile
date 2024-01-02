FROM node:21-alpine

WORKDIR /app
RUN apk update && apk upgrade && apk add bash vim --no-cache
RUN npm i -g @nestjs/cli
CMD npm install; npm run start:dev; sleep infinity; 
