# Specify a base image
FROM node:20-alpine3.17

# Specify a working directory
WORKDIR /usr/app

# copy the files in current directory to working directory
COPY package.json .

# Install some dpendencies
RUN npm install

COPY . .

# Default command
CMD ["npm","start"]