FROM node:14-alpine

WORKDIR /todo-app/front-end

ADD node_modules.tar.gz .

RUN npm install 

COPY . .

EXPOSE 3000

ENTRYPOINT [ "npm", "start" ]