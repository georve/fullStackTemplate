# Create mysql server based on the official image from the dockerhub
FROM mysql:5.7.18
# Add a database & root password
ENV MYSQL_DATABASE=auth_crm
ENV MYSQL_ROOT_PASSWORD=root
# optionnaly, run initial scripts for creating tables 
ADD ./sql-scripts/CreateDataBase.sql /docker-entrypoint-initdb.d/


