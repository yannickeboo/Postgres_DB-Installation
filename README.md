# Postgres_DB-Installation
```
sudo apt-get install wget ca-certificates
```
```
wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -
```
## Then, add the PostgreSQL repository by typing:
```
sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'
```
```
sudo apt-get update
sudo apt install postgresql postgresql-client
```
sudo systemctl stop postgresql.service
sudo systemctl start postgresql.service
sudo systemctl enable postgresql.service
```
```
sudo systemctl status postgresql.service
```

## connect to database
### logging to the postgres account
```
sudo su - postgres
psql
```
### If you are connected to PostgreSQL and want to see details of the connection, use the command:
```
\conninfo
```
### output should be like this:
![image](https://user-images.githubusercontent.com/85393914/169104577-92e4dc43-6442-43db-b27b-537ecbca902c.png)


