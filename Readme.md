This files contain Dummy SQL data in order to simulate a transaction database.

Why did I make this? I set out to learn more about Mysql as I believe that it is a very important skill for software engineers

How to run code:

Make sure that you have Mysql installed on your pc, with the UTF-8 configuration
As well as mysql workbench. The way to check the configuration of your database would be to first create a database, by typing the following in mysql workbench:

CREATE DATABASE `db1`;
use `db1`;
SELECT default_character_set_name FROM information_schema.SCHEMATA S WHERE schema_name = "db1";

If the output of this query is utf8 then you are all set to use/explore the database scripts by running create-Databases.sql script in mysql workbench using the lightning bolt icon. You can also run my queries by un commenting my queries.sql file Otherwise follow this guide:"https://www.a2hosting.com/kb/developer-corner/mysql/convert-mysql-database-utf-8" on how to change your mysql configuration.
