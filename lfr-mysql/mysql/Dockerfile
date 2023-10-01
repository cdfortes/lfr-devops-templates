# Use an official MySQL image as a parent image
FROM mysql:latest

# Copy custom configuration
COPY ./my.cnf /etc/mysql/my.cnf

# Copy DDL script
COPY ./lportal.sql /docker-entrypoint-initdb.d/lportal.sql