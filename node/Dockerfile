FROM node:lts-alpine

WORKDIR /app 

COPY . .
COPY ./src ../src

RUN npm install


EXPOSE 8080

CMD ["node", "index.js"]
