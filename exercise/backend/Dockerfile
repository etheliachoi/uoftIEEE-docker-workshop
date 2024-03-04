FROM node:18-alpine
WORKDIR /app
RUN npm install
COPY . .
ENV PORT=8000
EXPOSE 8000
CMD ["node", "index.js"]

# FROM: uses node:18-alpine as base image
# WORKDIR: sets the working directory of this docker container to /app
# RUN: runs the command `npm install` to install the dependencies
# COPY: copies everything from the current directory in local to current directory in docker
# ENV: sets the port to be 8000
# EXPOSE: makes port 8000 accessible to other services
# CMD: runs the command `PORT=8000 node index.js`
