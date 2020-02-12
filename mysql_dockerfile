FROM mysql
ENV MYSQL_ROOT_PASSWORD=password
ENV MYSQL_USER=user
ENV MYSQL_PASSWORD=pass
ENV MYSQL_DATABASE=test
COPY $PWD/src/mysql/ /docker-entrypoint-initdb.d/
