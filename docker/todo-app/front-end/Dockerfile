FROM node:14-alpine
WORKDIR /frontend 
COPY package*.json ./
# RUN npm install
COPY . .
ADD node_modules.tar.gz ./
EXPOSE 3000
CMD ["npm","start"]