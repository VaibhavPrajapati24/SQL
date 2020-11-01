
						<h1>SQL</h1>


<h2>Basic Commands Mysql</h2>

 **To Create Database**   
    `create database d1;`	   
 **To Show All Databases** 
    `show database;`	
 **To Use Database**
    `use database-name;`   
 **TO DELETE DATABASE**
    `drop database d1;`	
 **TO CREATE TABLE WHERE name, age IS COLUMN RESPECTED DATA TYPE char, int**	
    `create table t1(name char(20), age int );` 
 **TO INSERT VALUES INTO TABLE**
   `insert t1 values("name",20);` 	  
 **TO SHOW TABLES**
   `show tables;`	
 **TO DELETE ALL STORED DATA IN TABLE**		
   `delete from t1;`   
 **TO DELETE TABLE**        
   `drop table  t1, t2;`	
 **TO ADD NEW COLUMN IN TABLE**       
   `alter table t1 add Column-Name char(20);`
 **TO DELETE COLUMN IN TABLE**		
   `alter table t1 drop Column-Name;`		


<h3>Advance Commmands Mysql</h3>
`set password for user@localhost=password('password');` **TO SET OR RESET PASSWORD
`commit;`						**TO MAKE CHANGES PUBLICLY OF DATABASE'S DATA
`update t1 SET name='test' where age=20;              ` **TO CHANGE DATA IN COLUMN

**Some Operation Mysql**
* Union - Operation to fetch common output between two queries. but the number of columns and the data type of column's must be same to the both side of UNION
  `select name,age from t1 union select nickname, id from t2;`






					
