FROM postgres:17.2-alpine

COPY sql/01-CreateScheme.sql /docker-entrypoint-initdb.d/
COPY sql/02-InsertData.sql /docker-entrypoint-initdb.d/
