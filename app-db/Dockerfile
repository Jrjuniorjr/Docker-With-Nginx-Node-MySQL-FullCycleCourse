FROM mysql:5.7

ENV MYSQL_DATABASE=app-db
ENV MYSQL_ROOT_PASSWORD=root

COPY ./sql-scripts/ /docker-entrypoint-initdb.d/

CMD [ "--innodb-use-native-aio=0" ]