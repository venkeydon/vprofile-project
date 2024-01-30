FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Venkey"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE0="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
