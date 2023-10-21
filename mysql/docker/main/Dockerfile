FROM mysql:8.0-debian

RUN \
    apt-get update && \
    apt-get upgrade -y

COPY ./my.cnf /etc/mysql/conf.d
