FROM node:16

WORKDIR /usr/src/

COPY . .

RUN npm i && npm run build

EXPOSE 5000

CMD [ "npm", "start" ]