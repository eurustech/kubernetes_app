FROM node:9-alpine
COPY ./App /App
WORKDIR /App

RUN apk add --update nodejs
RUN npm install

EXPOSE 3000

# Start the app
CMD npm start