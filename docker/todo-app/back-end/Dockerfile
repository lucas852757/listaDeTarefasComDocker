FROM node:14-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
ADD node_modules.tar.gz /usr/src/app
CMD npm start
EXPOSE 3001
