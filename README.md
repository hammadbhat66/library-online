# library-online
$make --version

$sudo apt-get install libpq-dev

$sudo apt-get install postgresql postgresql-contrib

$service postgresql

$service postgresql status

$creatdb mybd3

$dropdb mydb3

$sudo su postgres

$psql

postgresql=#\l

postgresql=#\du

USER CREATION,PASSWORD CHANGE,ATTRIBUTE,DROP:

postgresql=#ALTER USER postgres WITH PASSWORD 'test123';

postgresql=#CREATE USER hammad WITH PASSWORD 'test122';

postgresql=#ALTER USER hammad WITH SUPERUSER;

postgresql=#DROP USER hammad;

CREATE DATABASE,SCHEMA,DELETE,INSERT,DROP,TRUNCATE

postgresql=#CREATE DATABASE mydb3;

postgresql=#CREATE SCHEMA mydb3schema;

postgresql=#CREATE TABLE mydb3schema.table1(id integer,password char(10)); 

postgresql=#select * from pg_catalog_tables;

postgresql=#select * from pg_catalog_tables where schemaname='mydb3schema';

postgresql=#INSERT into mydb3schema.table1 values(1,'1');

postgresql=##TRUNCATE mydb3schema.table1;

postgresql=#DELETE FROM mydb3schema.table1;

DROP TABLE mydb3schema.table1;


