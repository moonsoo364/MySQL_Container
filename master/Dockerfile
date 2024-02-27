FROM mysql:8.0.32
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=wtdb
ENV MYSQL_USER=dbo
ENV MYSQL_PASSWORD=welcome
COPY ./my.cnf /etc/mysql/my.cnf
COPY init.sql /docker-entrypoint-initdb.d/
EXPOSE 3306