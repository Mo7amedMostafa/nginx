# Use the official nginx base image
FROM nginx:latest

# Copy website content or application files
COPY ./html /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Start nginx
CMD ["nginx", "-g", "daemon off;"]
