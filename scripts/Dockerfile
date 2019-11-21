FROM mysql:5.7.15

# Autor
LABEL Luciano Ludueña

ENV MYSQL_DATABASE=competencias \ 
MYSQL_ROOT_PASSWORD=activarDB


ADD dump_base_de_datos.sql /docker-entrypoint-initdb.d

EXPOSE 3306
