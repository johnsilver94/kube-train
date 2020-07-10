FROM node:alpine3.12

COPY ./ /usr/src/app

WORKDIR /usr/src/app

RUN  npm install

EXPOSE 3002

CMD ["npm", "start"]