# u-develop-it

## Packages
```
npm init --y

npm install express mysql2

npm install jest --save-dev

mysql -u user -p
```


## MySql

To check out a database, type one of the following command on the mysql shell:
```
SHOW DATABASES;
SHOW SCHEMAS;
```

To select a database, run the following command:
```
SELECT schema_name
```

To run a database:
```
source db/schema.sql
source db/seeds.sql
```

To work on a database:
```
USE database_name;
```

To check content, use the codes below as examples:
```
SELECT * FROM voters;
SELECT first_name, last_name FROM voters;
SELECT email FROM voters WHERE id = 1;
```
