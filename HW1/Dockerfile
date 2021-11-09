FROM node:12
WORKDIR /usr/src/app/
COPY /frontend/package*.json ./
RUN npm install
COPY /frontend/src ./
COPY /frontend/public ./
EXPOSE 8080
CMD [ "node", "App.js" ]