
FROM ubuntu:latest

RUN apt-get update -y
RUN apt-get upgrade -y

RUN apt-get install nodejs -y
RUN apt-get install npm -y

RUN apt-get install git -y

RUN git clone https://github.com/tekstedt/express-test0.git

WORKDIR /express-test0
RUN npm install -y

EXPOSE 80
CMD ["node", "server.js"]
