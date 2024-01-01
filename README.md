# Connect-ec2-with-rds
This repo contains Commands to run on ec2 to connect it with RDS
# Prerequisites
- **Configure Security Group:** In the RDS instance settings, set up a security group that allows inbound traffic on the database port from your EC2 instance(s).
- Usually, this is port 3306 for MySQL/MariaDB, 5432 for PostgreSQL, or 1433 for SQL Server.
- Install Database Client Software on EC2
- Connect to your EC2 instance via SSH.
- Install the appropriate database client software, depending on the type of database you are using. For example, for MySQL, you might install the MySQL client.
```
```
# Establish Connection
- Once the client is installed, you can connect to your RDS instance using its endpoint. The general command format (MySQL used as an example) is:
```
mysql -h [rds-endpoint] -P [port] -u [username] -p
```
