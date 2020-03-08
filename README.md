# Test Connector
Test project for the integration of Mysql, Tomcat and Java13.
Even though it was made with transparency in mind, the program was made in Eclipse. Take this into consideration when using a different IDE

# Environment variables

Some envs are required for the test to work:
 - DB_HOST : host name of the Tomcat instance to connect to (Usually localhost).
 - DB_PORT : port of the host where Tomcat is listening for connections (Usually 3306).
 - DB_USER : Username to be used to access the database.
 - DB_PASSWORD : Password to be used to access the database.
 - DB_NAME : The name of the database to access to.

The environment variables listed above can both be configured at OS level or IDE level.
In case of Eclipse, the variables can be configured in Run > Run Configurations > Environment. 