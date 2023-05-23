FROM node:18.12-alpine

WORKDIR /vue

COPY . .

EXPOSE 8081

RUN npm install

RUN npm install bootstrap

CMD ["npm","run","serve"] 
