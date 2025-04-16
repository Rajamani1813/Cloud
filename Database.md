## RDS-(Relational Database Service)


	Data Base Configuration
-------------------------------------------------
```
sudo apt update

sudo apt install mysql-server -y
 
mysql -h endpoint-link -u admin -p
```

-----------------------------------------------------------


	## Create a Database 
	--------------------------------

	CREATE DATABASE mydatabase;

	## use the database 
	--------------------------------

	USE mydatabase;

	## list the database 
	--------------------------------

	SHOW DATABASES;s

	## Create a Table
	--------------------------------

	CREATE TABLE data (
  	  id INT AUTO_INCREMENT PRIMARY KEY,
   	 name VARCHAR(100) NOT NULL,
   	 age INT NOT NULL
	);

	## List the tables
	--------------------------------

	SHOW TABLES;

	DESC users;

	## Add the contents in the tables
	--------------------------------

	INSERT INTO data (name, age) VALUES ('kirthika', 00);
	INSERT INTO data (name, age) VALUES ('Arun', 00);

	## list the content in the table 
	--------------------------------

	SELECT * FROM data;
