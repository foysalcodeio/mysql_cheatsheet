best learning site for sql command :
```
https://devhints.io/mysql
https://www.mysqltutorial.org/mysql-cheat-sheet.aspx
https://gist.github.com/bradtraversy/c831baaad44343cc945e76c2e30927b3
```
## Log on as root user on MySQL
```
	mysql -u root
```
## List all Databases
```
	SHOW DATABASES; 
```

## Create a MySQL or MariaDB database
```
	CREATE DATABASE registration; 
```

## Deleting a MySQL or MariaDB database
```
	DROP DATABASE registration;
```
# Show tables
	use blog;
	show tables;
# all clear
	system cls

# create database using cli
```
CREATE TABLE registration(
    -> id INT NOT NULL,
    -> firstname VARCHAR(50),
    -> lastname VARCHAR(50),
    -> gender ENUM('m','f','o'),
    -> email VARCHAR(50),
    -> password VARCHAR(20),
    -> number VARCHAR(10));
```

# DESC registration

## setup table that means which table are insert data
```
$stmt = $conn->prepare("insert into student(firstName, lastName, gender, email, password, number) values(?, ?, ?, ?, ?, ?)");
```

# data insert for code command line
```
insert into student(firstName, lastName, gender, email, password, number) values(?, ?, ?, ?, ?, ?)
```

# get the data from table;
```
select * from registration;
select firstname from registration;
select email,number from registration;
select * from registration where password=123
```
# 1. [ database ki koraci sata abar save rakar jonno export gia click korta hobe]
# 2. [ onno kew ki ki data use korta tarjonno oi data.sql data k import korta hobe]





