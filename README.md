# mysql-basic-commands-arpitha-s
mysql-basic-commands-arpitha-s created by GitHub Classroom
 commands:   
mysql>show databases; //shows the created databases.
mysql>create database name; //create new databases.
mysql>show tables; //shows tables if any.
mysql>use databasename //to use specific database.
mysql>create table tablename(-----); //to create tables.
mysql>desc tablename; //to know description of attributes.
mysql>insert into tablename values(----); //to give values for attributes
mysql>select * from tablename; //to view contents of tables
mysql>select attributes from tablename where condition; // clauses of where condition
mysql>select count(*) from tablename; // to know count of attributes
mysql>update tablename set attirbute where condition; //to update any attribute if required
mysql>alter table tablename change attribute newattribute; //to change any attribute if required
mysql>alter table tablename add newattribute type; //to add any new attribute
mysql>alter table tablename modify attribute type; //to modify the type of attribute
mysql>select sum(attribute),avg(attribute),min(attribute),max(attribute) from tablename; //to know the sum,average,maximum and minimum 
                                                                          values of any attribute
mysql>alter table tablename drop attribute; //to drop any attribute
mysql>delete from tablename where condition; //to delete the tuble that is not required
mysql>select * from tablename order by attribute; //by default sorts in ascending order,to sort in descending orde "desc" should be 
                                                     given at the last
mysql>select sum(attribute) from tablename group by attribute; //to group the values of the attribute
mysql> select attribute,count(*) from tablename group by attribute having count(*); //to get the values of attribute using having condition
mysql>select distinct attribute from tablename; //to avoid duplication
mysql>create table tablename(---,primary key(attribute)); //to create attribute with unique key to avoid duplication
mysql>create table tablename(-----,foreign key(attribute) references tablename(attribute)); //foreign key is used to reference the primary 
                                                      key in same table or another table
mysql>select attribute from tablename1 t1,tablename t2 where attribute='',and t1.attribute=t2.attribute;
                                          //aliasing condition to join two attributes of different tables
mysql>commit; //to save the tables in datbase                                          
