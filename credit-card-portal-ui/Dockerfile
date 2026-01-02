# Build stage with Node 20
FROM node:20-alpine AS build
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm ci

# Copy source code
COPY . .

# Set API URL for production
ENV REACT_APP_API_URL=http://api-gateway:8080

# Build the app
RUN npm run build

# Production stage with Node 20
FROM node:20-alpine
WORKDIR /app

# Install serve globally
RUN npm install -g serve

# Copy build files
COPY --from=build /app/build ./build

# Expose port 3000
EXPOSE 3000

# Health check
HEALTHCHECK --interval=30s --timeout=3s --start-period=10s --retries=3 \
  CMD wget --no-verbose --tries=1 --spider http://localhost:3000 || exit 1

# Run serve on port 3000
CMD ["serve", "-s", "build", "-l", "3000"]






