FROM node:14

WORKDIR /kerokan-api
COPY package.json .
RUN npm install
COPY . .
CMD npm start
