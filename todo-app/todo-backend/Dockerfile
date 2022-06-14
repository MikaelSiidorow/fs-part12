FROM node:16

WORKDIR /usrc/src/app

COPY --chown=node:node . .

RUN npm ci

USER node

CMD npm start
