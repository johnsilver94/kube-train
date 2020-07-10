FROM node:alpine3.12

COPY ./ /usr/src/app

WORKDIR /usr/src/app

RUN  npm install

EXPOSE 3001

CMD ["npm", "start"]