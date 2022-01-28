FROM node:16-alpine3.14

WORKDIR /usr/src/app

COPY package.json ./
COPY package-lock.json ./
RUN yarn install
COPY . .

ENTRYPOINT ["npm", "run", "dev"]