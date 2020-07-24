# sfg-spring5-mysql
SFG Tutorial on Spring 5 - MySQL for Java Developers

## Section 16 - Introduction and Installation of MySQL
## Section 17 - Connecting to MySQL
### `297` MySQL Command Line for OSX & Linux
- I run Docker container with mysql
```
docker run --name art-mysql -v /home/art/dockerdata/mysql:/var/lib/mysql -p 3306:3306 -e MYSQL_ALLOW_EMPTY_PASSWORD=yes -d mysql
```
- I installed command line client
```
sudo apt install mysql-client-core-5.7
```
- then connected to mysql server
```
 mysql -h 127.0.0.1 -P 3306 -u root -p
 ```
 - `mysql> status;`
 - `show databases;`
 - `use mysql;` - switch to certain database
 - `show tables;`
 - `describe user;` - show table structure
 - `select host, user  from user;`
 - `exit;`
