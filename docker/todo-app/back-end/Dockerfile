# Foram consultados os links abaixo:
#Source: https://app.betrybe.com/course/back-end/docker/manipulacao-e-criacao-de-imagens-no-docker/e92d2393-3508-43ab-8a67-2b2516d25864/conteudos/f8a69cf0-e5e7-4088-b0c9-176a0a7f8787/dockerfile-comandos-basicos/7008bda9-816c-489d-bc3c-3f2febbfcc6b?use_case=next_button

# Source: https://trybecourse.slack.com/files/U01FVPAM2N6/F039DB1RQLR/parte_2.mp4

FROM node:14-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
ADD node_modules.tar.gz /usr/src/app
CMD npm start
EXPOSE 3001
