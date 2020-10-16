FROM postgres:10-alpine

ENV LANG cs_CZ.utf8
ENV TZ='Europe/Prague'

COPY ./00*.sh /docker-entrypoint-initdb.d/
COPY ./*.conf /
