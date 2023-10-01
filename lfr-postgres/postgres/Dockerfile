# Use an official MySQL image as a parent image
FROM postgres:latest

# Copy custom configuration
COPY ./my.cnf /etc/postgres/my.cnf

# Copy DDL script
COPY ./lportal.sql /docker-entrypoint-initdb.d/lportal.sql