
						<h1>SQL</h1>


<h2>Basic Commands Mysql</h2>

 **To Create Database**   
    `create database d1;`	   
 **To Show All Databases**
    `show database;`	
 **To Use Database**
    `use database-name;`   
 		
`drop database d1;`		**TO DELETE DATABASE
`create table t1(name char(20), age int );`**TO CREATE TABLE WHERE name, age IS COLUMN RESPECTED DATA TYPE char, int 
`insert t1 values("name",20);` 	  	**TO INSERT VALUES INTO TABLE 
`show tables;`		**TO SHOW TABLES	
`delete from t1;`             **TO DELETE ALL STORED DATA IN TABLE
`drop table  t1, t2;`	        **TO DELETE TABLE
`alter table t1 add Column-Name char(20);`		**TO ADD NEW COLUMN IN TABLE
`alter table t1 drop Column-Name;`		**TO DELETE COLUMN IN TABLE


<h3>Advance Commmands Mysql</h3>
`set password for user@localhost=password('password');` **TO SET OR RESET PASSWORD
`commit;`						**TO MAKE CHANGES PUBLICLY OF DATABASE'S DATA
`update t1 SET name='test' where age=20;              ` **TO CHANGE DATA IN COLUMN

**Some Operation Mysql**
* Union - Operation to fetch common output between two queries. but the number of columns and the data type of column's must be same to the both side of UNION
  `select name,age from t1 union select nickname, id from t2;`






					
