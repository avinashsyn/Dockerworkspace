#specify the base image
FROM node:alpine

WORKDIR /usr/app

#install some dependencies
COPY ./package.json ./
#only when package.json
RUN npm install

COPY ./ ./

#default command
CMD ["npm","start"]