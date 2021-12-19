# pull official base image
FROM mysql/mysql-server:latest

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
