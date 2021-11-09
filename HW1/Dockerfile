FROM node:12
WORKDIR /usr/src/app/
COPY /frontend/package*.json ./
RUN npm install
COPY /frontend ./
RUN ls -la
RUN npm run build
RUN npm start
EXPOSE 8080
CMD [ "node", "src/App.js" ]