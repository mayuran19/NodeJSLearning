FROM node:8.4.0-alpine

RUN mkdir /app
WORKDIR /app

COPY package.json /app
RUN npm install

COPY . /app

EXPOSE 3000

#No need to execute this as this will be invoked from docker-componse
#CMD ["npm", "start"]