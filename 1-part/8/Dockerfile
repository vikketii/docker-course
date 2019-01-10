FROM ubuntu:16.04

RUN apt-get update && apt-get install -y curl \
    && curl -sL https://deb.nodesource.com/setup_10.x | bash \
    && apt-get install -y nodejs

RUN npm install 30-seconds-of-code

CMD node