# Use a Node.js base image
FROM node:14

# Set working directory
WORKDIR /usr/src/app

# Copy application files
COPY . .

# Install dependencies
RUN npm install

# Expose the port
EXPOSE 3000

# Command to run the application
CMD [ "node", "patient-service.js" ]
