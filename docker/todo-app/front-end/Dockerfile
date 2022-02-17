FROM node:14-alpine

EXPOSE 3000

WORKDIR /frontEnd

ADD ./node_modules.tar.gz /frontEnd

COPY ./ /frontEnd

ENTRYPOINT [ "npm", "start" ]