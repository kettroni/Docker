FROM ubuntu:16.04

RUN apt-get update
RUN apt-get install -y curl 
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt-get install -y nodejs
COPY backend-example-docker .
RUN npm install
EXPOSE 8000
CMD FRONT_URL=http://localhost:5000 npm start
