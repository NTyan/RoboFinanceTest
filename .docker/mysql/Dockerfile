FROM mysql:5.7

COPY ./data/tables.sql /docker-entrypoint-initdb.d/
COPY ./data/db /home/db
ADD ./data/tables.sql /docker-entrypoint-initdb.d
RUN chmod a+r /docker-entrypoint-initdb.d/*
RUN chown -R mysql:mysql /docker-entrypoint-initdb.d/*