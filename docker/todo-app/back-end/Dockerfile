FROM node:14.4-alpine3.11

EXPOSE 3001

WORKDIR /back-end/

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm", "start" ]
