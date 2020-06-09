FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD adsis-eusebia
ENV MYSQL_DATABASE db_tugas5
ENV MYSQL_USER admin
ENV MYSQL_PASSWORD adsis-eusebia
ADD script.sql /docker-entrypoint-initdb.d
EXPOSE 3306