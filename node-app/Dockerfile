# Base Image
# Official lightweight Node.js image
FROM node:18-alpine

# Set working directory
WORKDIR /app

# Copy package.json first
COPY package.json .

# Install Node.js dependencies
RUN npm install 

# Copy application source code
COPY . .

# Expose application port
EXPOSE 3000

# Start Node.js application
CMD ["node", "index.js"]
