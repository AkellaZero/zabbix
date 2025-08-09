FROM zabbix/zabbix-server-pgsql:latest
USER root
RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    pip3 install --no-cache-dir \
    requests \
    pandas \
    numpy \
    psycopg2-binary
USER zabbix
