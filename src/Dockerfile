FROM postgres:9.5-alpine

ENV LANG cs_CZ.utf8
ENV TZ='Europe/Prague'

COPY ./001-add-pg-config.sh /docker-entrypoint-initdb.d/
COPY ./002-init.sh /docker-entrypoint-initdb.d/
COPY ./postgresql-extend.conf /

EXPOSE 5432
