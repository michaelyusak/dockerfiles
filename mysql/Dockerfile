# Use the official MySQL image from Docker Hub
FROM mysql:latest

# Set environment variables for MySQL
ENV MYSQL_USER=mysql \
    MYSQL_PASSWORD=password \
    MYSQL_ROOT_PASSWORD=password

# Expose the MySQL port
EXPOSE 3306

# Default command to run the MySQL server
CMD ["mysqld"]