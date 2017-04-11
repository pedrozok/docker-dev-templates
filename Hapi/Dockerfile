FROM node:argon
MAINTAINER zok

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

# Install app dependencies and bundle app source
COPY . /usr/src/app
RUN npm install

EXPOSE 3030

CMD [ "node", "./server.js" ]
