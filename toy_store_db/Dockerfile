from mysql:5.7

ENV MYSQL_ROOT_PASSWORD root
ENV MYSQL_DATABASE  toystore

COPY ./toystore-test.sql /docker-entrypoint-initdb.d/
