# Use the official Node.js 16 image
FROM node:16-alpine

# Create app directory
WORKDIR /usr/src/app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Bundle app source
COPY . .

# Expose the port
EXPOSE 8080

# Start the application
CMD ["npm", "start"]