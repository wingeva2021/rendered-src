FROM node:lts-alpine

WORKDIR /app 

COPY . .
COPY ./src ../src

RUN npm install

RUN chmod +x ./setup.sh

RUN ./setup.sh

EXPOSE 8080

CMD ["node", "index.js"]
