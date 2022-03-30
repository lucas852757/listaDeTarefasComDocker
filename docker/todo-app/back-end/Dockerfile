FROM node:14-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
ADD node_modules.tar.gz /app
EXPOSE 3001
CMD ["npm","start"]
