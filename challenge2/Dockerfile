# Use Node.js image as base
FROM node:latest




# Set the directory in the container
WORKDIR /app



# Copy package.json and package-lock.json to the directory
COPY package*.json ./




# Install all dependencies
RUN npm install




# Copy the rest of the files
COPY . .




# Expose port 3000 to the outside
EXPOSE 3000




# Command to run the application
CMD ["node", "server.js"]
