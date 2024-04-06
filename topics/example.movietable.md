[<<<----- Basic Command (Create, Alter, Drop, Add, Update, Delete)](../../../topics/basic.commands.md)
# 1.1 - Example 1 

## Movie Table

![devrimmehmet](https://raw.githubusercontent.com/devrimmehmet/SQL/main/images/table-for-example.png)

---
### Step 1 : Create Database
```sql
create database devrimmehmet;
```

<details>
  <summary>
  Don't forget to change the database here (pay attention to the red rectangle)
  </summary>

![dont-forget-change-db](https://raw.githubusercontent.com/devrimmehmet/SQL/main/images/select-table-and-execute.png)
</details>
<details>
  <summary>
Press here to run (pay attention to the green rectangle)
  </summary>

![dont-forget-change-db](https://raw.githubusercontent.com/devrimmehmet/SQL/main/images/select-table-and-execute.png)
</details>
<details>
  <summary>
Go by constantly checking what you have done with a select query.(pay attention to the blue rectangle)
  </summary>

![dont-forget-change-db](https://raw.githubusercontent.com/devrimmehmet/SQL/main/images/select-table-and-execute.png)
</details>





### Step 2 : Create Tables
```sql
create table users(user_id int, first_name varchar(100), last_name varchar(100), email varchar(255), encrypted_password varchar(1000));
create table movies (movie_id int, title varchar(100), description varchar(100), price varchar(255));
create table purchases(user_id int, movie_id int, purchase_date varchar(255), purchase_price varchar(100));
```
### Step 3 : Add rows ( Insert )
```sql
insert into movies (movie_id,title,description,price) values (1,'The Last Of Castle', 'Movie or Documentary', 4.99)
insert into movies (title,price) values ('Into The Wild', 6.99)
insert into movies (title,price) values ('Eternal sunshine of the spotless mind', 7.99)
insert into movies (title,price) values ('Soul', 8.88)
insert into movies (title,price) values ('Test', 9.99)
```
### Step 4 : Select
```sql
select * from movies
select title, price from movies
```
### Step 5 : Order By [column] --> Ascending sort 
```sql
select title, price from movies order by price; 
```
### Step 6 : Order By [column] --> Descending sort 
```sql
select title, price from movies order by price desc;
```
### Step 7 : Update
```sql
update movies set price=0.99 where title='Soul' 
select * from movies
```
### Step 8 : Delete

```sql
delete from movies where title='Test'
select * from movies
```


[----->>> Relational Databases](../../../topics/relational.databases.md)