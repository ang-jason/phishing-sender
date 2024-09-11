# Use the official Nginx image from Docker Hub
FROM nginx:alpine

# Copy the HTML and JS files to the Nginx web server
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]
