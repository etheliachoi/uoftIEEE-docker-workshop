FROM node:18-alpine
WORKDIR /app
COPY . .
ENV REACT_APP_BACKEND_URL=http://localhost:8000
RUN npm install
CMD ["npm", "run", "start"]

# FROM: uses node:18-alpine as base image
# WORKDIR: sets the working directory of this docker container to /app
# COPY: copies everything from the current directory in local to current directory in docker
# ENV: creates an environment variable; `export REACT_APP_BACKEND_URL=...` in terminal; ensures that frontend knows which port backend listens on
# RUN: runs the command `npm install` to install the dependencies
# CMD: runs the command `npm run start` to launch the application