FROM mysql:8.0
COPY master-data.sql /docker-entrypoint-initdb.d/
COPY app-user.sql /docker-entrypoint-initdb.d/
ENV MYSQL_ROOT_PASSWORD="RoboShop@1"
EXPOSE 3306