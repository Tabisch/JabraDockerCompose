# JabraDockerCompose

Ready to Deploy docker-compose for jabra xpress

Unpack the Zip, change your Top Level Domain to your own.

![image](https://user-images.githubusercontent.com/26881335/187153430-c39c7a5c-f963-46d0-bc35-0059ca19a3ab.png)

Docker-Compose up -d

Run this command to initialize the database

docker run --network jabraxpress_default -e MSSQLServerConnectionString="Server=tcp:sqlserver,1433;Initial Catalog=xpress;User ID=sa;Password=mssql1Ipw;Connection Timeout=30;" -it gnaudio/jabra-xpress-databaseconsoletool:v5.1.17202 -seed

restart the docker compose

Open Nginx Proxy Manager on port 81

Setup Entries in Nginx Proxy Manager

![image](https://user-images.githubusercontent.com/26881335/187152929-3f903fe4-5543-4482-adc4-960d82c66a77.png)

the install should be done now
