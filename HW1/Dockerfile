FROM node:16
WORKDIR /usr/src/app/
RUN npm install express --save
COPY /index.js ./
RUN ls -la
EXPOSE 80
CMD [ "node", "index.js" ]