# DataBase

* For Creating Database
```
create databse dtatabaseName;
	
```

* For Showing Databs
```
show databases;
	
```

* For Showing Tables
```
show tables;
	
```

* For Removing database completly
```
drop databaseName;
	
```


* For Creating database
```
use test;
	create table student(
		id int primary key auto_increment,
	    first_name varchar(50) not null,
	    last_name varchar(50) not null,
	    date_of_birth date 
	);
or 
	create table test.student(
		id int primary key auto_increment,
	    first_name varchar(50) not null,
	    last_name varchar(50) not null,
	    date_of_birth date 
	);

	
```
* For Creating Databs
```
-- example
	
```
