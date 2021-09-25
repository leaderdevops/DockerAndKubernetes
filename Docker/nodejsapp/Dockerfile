FROM node:14.17.6-alpine3.12
WORKDIR /app
ADD package*.json ./
RUN npm install
ADD . .
CMD node index.js