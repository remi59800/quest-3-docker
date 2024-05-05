FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install --silent

COPY . ./

CMD npm run dev