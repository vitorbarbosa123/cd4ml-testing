FROM postgres:12.2
RUN apt-get update && apt-get install -y wget unzip && \
    mkdir -p /docker-entrypoint-initdb.d && \
    wget https://github.com/alura-cursos/continuous-delivery-for-machine-learning-data/raw/main/store47-2016.zip -O /docker-entrypoint-initdb.d/store47-2016.zip && \
    unzip /docker-entrypoint-initdb.d/store47-2016.zip -d /docker-entrypoint-initdb.d/

COPY initialize.sql /docker-entrypoint-initdb.d/initialize.sql
