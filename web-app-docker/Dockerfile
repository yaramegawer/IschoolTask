# Use Node.js 18 as base image
FROM node:18

# Set working directory inside container
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .
RUN npm install

# Copy the rest of the app
COPY . .

# Expose port 3000
EXPOSE 3000

# Command to start the app
CMD ["npm", "start"]
