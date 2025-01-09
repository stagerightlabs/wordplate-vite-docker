FROM node:22-alpine

LABEL authors="Ryan Durham <ryan@stagerightlabs.com>"

WORKDIR /var/www

RUN yarn set version stable

USER node

CMD [ "yarn", "dev" ]
