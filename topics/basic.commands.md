###  Create Database

```sql
create database social_network;
```
---

###  Create Table

```sql
create table users(user_id int,first_name VARCHAR(100),last_name VARCHAR(100),email VARCHAR(255)); 
```

### Update Table Add

```sql
alter table users add encrypted_password varchar(1000);
```

### Delete a Column From The Table 

```sql
Alter Table users Drop Column email;
```

### Delete Table 

```sql
Drop Table users;
```

### Delete Database 

```sql
Drop database social_network;
```
