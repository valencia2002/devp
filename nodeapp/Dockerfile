FROM node:14
WORKDIR /user/app
COPY package.json .
RUN npm install
EXPOSE 8080
CMD [ "nose", "app.js" ]