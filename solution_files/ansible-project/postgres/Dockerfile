FROM postgres

COPY ./init.sql /docker-entrypoint-initdb.d/

EXPOSE 5432   
#5432 developer kafasına göre yazmış 9000 de olabilrdi


# https://hub.docker.com/_/postgres  ==> developrein yazmış olduğu init.sql kopyalamanın yayını
# PGDATA volume kaybolmamsı için alan var.
# /var/lib/postgresql ==> hosta volume bağlayacağız.
