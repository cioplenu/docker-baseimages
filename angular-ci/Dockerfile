FROM node:16-bulseye

RUN apt-get update                                                                                             \
    && apt-get install -y chromium git wget unzip jq                                                           \
    && yarn global add @angular/cli --network-timeout 100000                                                   \
    && git config --global user.email "git@localhost"                                                          \
    && git config --global user.name "git"

COPY assets/* /opt/

ENV CHROME_BIN=/usr/bin/chromium

