FROM mysql:8.2
RUN chown -R mysql:root /var/lib/mysql/

ARG DB_DATABASE
ARG DB_USERNAME
ARG DB_PASSWORD

ENV MYSQL_DATABASE=$MYSQL_DATABASE
ENV MYSQL_USER=$MYSQL_USER
ENV MYSQL_PASSWORD=$MYSQL_PASSWORD

EXPOSE 3306
