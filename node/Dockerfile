# Build off this base image
FROM node:7

# Set up app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package.json /usr/src/app/
RUN yarn install

# Bundle app source
COPY . /usr/src/app

# Expose the server to the host machine
EXPOSE 8080

# Run this command on startup
ENTRYPOINT ["yarn", "start"]