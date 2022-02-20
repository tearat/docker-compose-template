FROM node:14-slim

WORKDIR /client
COPY ./ /client

RUN yarn install && yarn build

ENTRYPOINT ["npx", "serve", "-s", "build"]