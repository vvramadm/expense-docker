FROM node:24.1.0-slim
EXPOSE 8080
ENV DB_HOST="mysql"
RUN mkdir /opt/server
WORKDIR /opt/server 
COPY package.json  .
COPY *.js  .
RUN  npm install
CMD  ["node","index.js"]
#ENV DB_HOST="mysql"
 