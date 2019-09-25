FROM node:alpine

RUN apk --update add redis

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

RUN chmode 777 start.sh

CMD ["./start.sh"]