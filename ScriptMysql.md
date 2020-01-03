sudo mysql 

create databse dtatabaseName;
show databases;
use databaseName;
show tables;
drop databaseName; -- remove completly database



use test;
create table student(
	id int primary key auto_increment,
    first_name varchar(50) not null,
    last_name varchar(50) not null,
    date_of_birth date 
);


insert into tableName
(first_name,last_name,date_of_birth)
values
("Ali12","Sharifazde","1999-10-24"),-- one or more
("Ali2","Sharifazde","1999-10-24"),
("Ali3","Sharifazde","1999-10-24"),
("Ali4","Sharifazde","1999-10-24"),
("Ali5","Sharifazde","1999-10-24"),
("Ali6","Sharifazde","1999-10-24"),
("Ali7","Sharifazde","1999-10-24"),
("Ali8","Sharifazde","1999-10-24"),
("Ali10","Sharifazde","1999-10-24");


select * from student;
select first_name,last_name,date_of_birth from student;
select first_name as 'First Name',
last_name as 'Last Name',
date_of_birth as 'Date of Birth' 
from student;
* Once successfully built, you can run the service by one of these two methods:
```
        java -jar -Dspring.profiles.active=test target/spring-boot-rest-example-0.5.0.war
or
        mvn spring-boot:run -Drun.arguments="spring.profiles.active=test"
```
* Check the stdout or boot_example.log file to make sure no exceptions are thrown
