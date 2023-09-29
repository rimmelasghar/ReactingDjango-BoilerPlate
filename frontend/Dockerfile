FROM node:16

WORKDIR /frontend

COPY . /frontend

RUN yarn install

RUN yarn build

EXPOSE 3000

CMD ["yarn", "start"]
