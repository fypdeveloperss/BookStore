# Use Node image
FROM node:18

# Create app directory
WORKDIR /app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Bundle app source
COPY . .

# Expose backend port
EXPOSE 5555

# Start backend
CMD ["node", "index.js"]

