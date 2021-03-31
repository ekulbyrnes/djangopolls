FROM mysql:5.7
# Add wildcard (%) to end of database name in GRANT statement"
RUN sed -i 's:\${MYSQL_DATABASE//_/\\\\_}:&%:' /usr/local/bin/docker-entrypoint.sh
