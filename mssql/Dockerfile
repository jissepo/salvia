# https://hub.docker.com/_/microsoft-mssql-server
FROM mcr.microsoft.com/mssql/server:2019-latest

WORKDIR /usr/src

# Copy files over
COPY . /usr/src

ENTRYPOINT /bin/bash ./entrypoint.sh

