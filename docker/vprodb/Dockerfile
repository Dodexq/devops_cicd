FROM mysql:5.7.25
LABEL "Author" = "Artem Udodov"
LABEL "Project" = "devopsclass"
ENV MYSQL_ROOT_PASSWORD="admin123"
ENV MYSQL_DATABASE="accounts"
ADD docker/vprodb/db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
EXPOSE 3306