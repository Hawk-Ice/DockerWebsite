# Use an official Node.js image as the base image
FROM node:14

# Set the working directory within the container
WORKDIR /app

# Copy your Node.js application code and package.json to the container
COPY ./ /app

# Install dependencies
RUN npm install

# Specify the command to start your Node.js application
CMD ["npm", "start"]
