FROM node:10

RUN mkdir app

COPY ./src /app/src/

WORKDIR /app/src

RUN npm install

EXPOSE 7777

CMD ["npm", "prod"]
