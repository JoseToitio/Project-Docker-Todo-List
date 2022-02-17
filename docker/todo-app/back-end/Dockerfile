FROM node:14-alpine

WORKDIR /backEnd

EXPOSE 3001

COPY ./ /backEnd

ADD ./node_modules.tar.gz ./

ENTRYPOINT [ "npm", "start" ]