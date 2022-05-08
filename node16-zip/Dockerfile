FROM node:16

RUN apt-get update \
 && apt-get install -y --no-install-recommends \
    zip \
 && apt-get clean \
 && rm -rf /var/lib/apt/lists/*
 
