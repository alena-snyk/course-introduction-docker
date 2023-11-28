FROM mysql:5.7.44
COPY ./initial/initial_data.sql /docker-entrypoint-initdb.d/
RUN ["/usr/local/bin/docker-entrypoint.sh"]