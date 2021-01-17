FROM node:12.8-alpine
WORKDIR /usr/src/app
COPY ./* ./
RUN npm install
COPY . .
EXPOSE 80
CMD ["node", "./server.js" ]