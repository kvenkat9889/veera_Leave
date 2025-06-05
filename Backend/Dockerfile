# Use Node.js base image
FROM node:18

# Create app directory
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy source
COPY . .

# Expose port and start server
EXPOSE 3016
CMD ["node", "Server.js"]

