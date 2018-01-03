FROM node

MAINTAINER mohammad

WORKDIR /src

# COPY . /src
VOLUME /c/Users/moein/mean-docker-compose/node-app:/src

RUN npm install

RUN npm install -g nodemon

EXPOSE 3000

CMD [ "npm","start" ]
