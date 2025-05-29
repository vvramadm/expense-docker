FROM node:24.1.0-alpine3.21
EXPOSE 8080
ENV DB_HOST="localhost"
RUN mkdir /opt/server
WORKDIR /opt/server 
COPY package.json  .
COPY *.js  .
RUN  npm install
CMD  ["node","index.js"]
#ENV DB_HOST="mysql"
 