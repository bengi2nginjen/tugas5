FROM mysql:latest

#ENV MYSQL_ROOT_PASSWORD
ENV MYSQL_DATABASE db-tugas5
ENV MYSQL_USER root
ENV MYSQL_PASSWORD tugas5-eusebia
ADD script.sql /docker-entrypoint-initdb.d
EXPOSE 3306