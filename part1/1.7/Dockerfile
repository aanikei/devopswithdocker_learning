FROM ubuntu:22.04

WORKDIR /usr/src/app

RUN apt-get -qq update; apt-get -y install curl > /dev/null

COPY script.sh .

CMD ./script.sh
