FROM node:current-alpine3.10

WORKDIR /app
ENV PATH /app/node_modules/.bin:$PATH
COPY package.json ./
COPY yarn.lock ./
RUN yarn install

CMD ["yarn", "start"]