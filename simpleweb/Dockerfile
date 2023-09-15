#base image
FROM node:14-alpine

#Install dependencies
WORKDIR /usr/app

#only package.json is required for installing npm
COPY ./package.json ./
RUN npm install

COPY ./ ./

#default command
CMD ["npm", "start"]