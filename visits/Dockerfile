#Specify base image
FROM node:alpine

#Chnage the working directory
WORKDIR '/app'

#Require activity
COPY ./package.json .
RUN npm install
COPY . .

#Default command
CMD ["npm", "start"]