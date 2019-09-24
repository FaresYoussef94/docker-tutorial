#Specify the base image
FROM node:alpine

#Install dependency 
WORKDIR /usr/app
COPY ./ ./
RUN npm install

#Default command
CMD ["npm","start"]