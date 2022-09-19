FROM node
LABEL author="Thomas GEOFFRON"

RUN apt-get update && apt-get install -y 

WORKDIR /app

COPY . .

RUN npm install \
    npm test