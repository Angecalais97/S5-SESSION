FROM node:17
WORKDIR /usr/src/app
COPY package*.json ./usr/src/app
RUN npm install
COPY . .
EXPOSE 3000
ENTRYPOINT ["node"]
CMD [ "app.js" ]
