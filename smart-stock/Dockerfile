# Line 2 explanation: Pull a lightweight, secure base image
FROM nginx:alpine

# Line 5 explanation: Copy frontend code into default Nginx web root
COPY index.html /usr/share/nginx/html/index.html

# Line 8 explanation: Expose port 80 for incoming web traffic
EXPOSE 80

# Run Nginx in foreground
CMD ["nginx", "-g", "daemon off;"]