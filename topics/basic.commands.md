# 1 - Basic SQL Commands && Basit SQL Komutları
## Create, Alter, Drop, Add, Update, Delete && Oluştur, Güncelle, Sil, Ekle, Güncelle, Sil
---
###  Create Database && Veritabanı Oluştur

```sql
create database social_network;
```

###  Create Table && Tablo Oluştur

```sql
create table users(user_id int,first_name VARCHAR(100),last_name VARCHAR(100),email VARCHAR(255)); 
```

### Update Table Add && Tablo Güncelleme (Kolon Ekleme)

```sql
alter table users add encrypted_password varchar(1000);
```

### Delete a Column From The Table && Tablo Güncelleme ( Kolon Silme )

```sql
Alter Table users Drop Column email;
```

### Delete Table && Tablo Silme

```sql
Drop Table users;
```

### Delete Database && Veritabanı Silme

```sql
Drop database social_network;
```


---

[----->>> Example 1 - MovieTable && Örnek 1](../../../blob/main/topics/example.movietable.md)
