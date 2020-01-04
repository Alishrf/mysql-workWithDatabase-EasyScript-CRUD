# Create
* For Inserting And Creating 
```
use test;
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
```

# Reading
* For Selecting All Data From  Database
```
select * from student;

```
* For Selecting All Data From  Database Just Show first_name column  as 'First Name' ,last_name column  as 'Last Name' ,...
```
select first_name,last_name,date_of_birth from student;
select first_name as 'First Name',
last_name as 'Last Name',
date_of_birth as 'Date of Birth' 
from student;

```

* Retriew data with limi 2 

```
SELECT * FROM test.student limit 2;

```

* Retrieve only students that  their firstname is 'ALi'
```
select first_name,last_name from test.student where first_name = 'Ali';
```

* Retrieve only students with word 'Ali' in their lastname
```
select first_name,last_name from test.student where first_name like '%ALi%';
```

* Retrieve only students start with word 'Ali' in their lastname
```
select first_name,last_name from test.student where first_name like 'ALi%';
```

* Retrieve only students end with word 'Ali' in their lastname
```
select first_name,last_name from test.student where first_name like '%ALi';
```

* Retrieve only FULL NAME of Students
```
select concat(first_name," ",last_name) 'Full Name' from test.student;
```

* Retrieve only course with 'number of credits' more than 3
```
select * from course where number_of_credits > 3;
```

* Retrieve only course with 'number of credits' more than 3
```
select * from course where number_of_credits > 3;
```









