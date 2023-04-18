# Set a base image
FROM alpine
# Create a work of directory
WORKDIR /usr/app 
# Run commands
RUN apk add --update redis 
# Set default command
CMD ["redis-server"]