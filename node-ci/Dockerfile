FROM node:lts

LABEL maintainer="Anian Ziegler" \
      email="it@cioplenu.de"

RUN apt-get update && apt-get install ghostscript libgs-dev -y && rm -rf /var/lib/apt/lists/*

# Needed for ghostscript4js
ENV GS4JS_HOME=/usr/lib/x86_64-linux-gnu
