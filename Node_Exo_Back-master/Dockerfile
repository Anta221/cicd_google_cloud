FROM node:latest


WORKDIR /home/node/app


COPY ["package.json", "package-lock.json*", "./"]

RUN npm install


# Bundle app source
COPY . .

EXPOSE 8080
CMD [ "node", "server.js" ]
