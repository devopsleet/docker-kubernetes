# Specify a base image
FROM node:14-alpine

WORKDIR /usr/app

COPY ./ ./

# Install dependencies
RUN npm install

# Default command
CMD ["npm","start"]