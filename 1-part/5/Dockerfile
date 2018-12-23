FROM ubuntu:16.04

WORKDIR /app
# When build inside app folder, we can use '.'
COPY . /app

RUN apt-get update && apt-get install -y curl

RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt-get install -y nodejs

RUN npm install

EXPOSE 5000

CMD npm start


