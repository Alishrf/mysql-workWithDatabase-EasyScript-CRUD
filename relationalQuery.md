
* inner join

```
SELECT stu.first_name , stu.last_name , cou.name as 'course name' FROM test.class cl
inner join test.student stu on cl.student_id = stu.id 
inner join test.course cou on cl.course_id = cou.id;
```

 
* will select all left table items whether or not nmatch conditions
```
select * from test.class cl
left join test.course co on cl.course_id= co.id; 
```

* the opposite of above
```
select * from test.class cl
right join test.course co on cl.course_id= co.id;
```

```
select * from test.class cl
cross join test.course co on cl.course_id= co.id;
```
