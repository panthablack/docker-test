# syntax=docker/dockerfile:1

# Use the base image mysql:latest
FROM mysql:latest

# Set environment variables
ENV MYSQL_DATABASE main
ENV MYSQL_ROOT_PASSWORD secret

# Copy custom scripts or configuration files from your host to the container
COPY ./scripts/ /docker-entrypoint-initdb.d/