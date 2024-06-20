FROM ubuntu:22.04

WORKDIR /usr/src/app

COPY script.sh .

RUN chmod a+x ./script.sh

RUN apt update && apt install curl -y

CMD ./script.sh
