FROM mysql:latest

COPY ./products.csv /products.csv
COPY ./users.csv /users.csv
COPY ./setup.sql /docker-entrypoint-initdb.d/setup.sql

COPY ./migrate.sql /migrate.sql
COPY ./seed.sql /seed.sql

ENTRYPOINT ["/entrypoint.sh"]
CMD ["mysqld", "--secure-file-priv=/"]
#CMD ["--secure-file-priv=/"]
