FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD root
ENV MYSQL_DATABASE db_tugas5
ENV MYSQL_USER eusebia
ENV MYSQL_PASSWORD tugas5_eusebia
ADD script.sql /docker-entrypoint-initdb.d
EXPOSE 3306