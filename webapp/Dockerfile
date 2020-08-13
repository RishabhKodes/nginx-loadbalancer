# Use a standard Node image from Docker Hub 
FROM node:latest

RUN mkdir -p /backend-dir-inside-container

# Set this as the default, working directory.
# We'll land here when we SSH into the container.
WORKDIR /backend-dir-inside-container

ADD ./src /backend-dir-inside-container

RUN  npm install

EXPOSE 3000

CMD  ["node", "app.js"]
