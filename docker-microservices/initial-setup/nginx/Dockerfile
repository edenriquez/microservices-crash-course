# Pull base image.
FROM nginx
# dockerhub

# Define working directory.
WORKDIR /etc/nginx

COPY ./nginx-dynamic-servers.conf /etc/nginx
# Define default command.
CMD ["nginx", "-g", "daemon off;"]

# Expose ports.
EXPOSE 80
EXPOSE 443
