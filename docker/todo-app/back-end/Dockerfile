FROM node:14-alpine3.15

WORKDIR /app

add node_modules.tar.gz .
COPY . .

EXPOSE 3001

ENTRYPOINT ["npm", "start"]