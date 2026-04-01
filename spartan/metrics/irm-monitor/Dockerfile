FROM node:25.8.2

WORKDIR /usr/src/app

COPY . .

RUN corepack enable && yarn install

RUN yarn build

EXPOSE 8080

CMD ["node", "dist/index.js"]
