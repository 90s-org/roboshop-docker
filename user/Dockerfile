FROM node:20
# this creates /app and move there
WORKDIR /app
EXPOSE 8080
COPY *.js .
COPY package.json .
RUN npm install
CMD ["node", "server.js"]