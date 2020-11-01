
						<h1>SQL</h1>


<h2>Basic Commands Mysql</h2>

 **To Create Database**   
 `create database d1;`	
   
 **To Show All Databases**     
  `show database;`	

 **To Use Database**   
 `use database-name;`   

 **To Delete Database**  
 `drop database d1;`
	
 **To Create Table With Column name, age Respectively Data Type char, int**	         
  `create table t1(name char(20), age int );` 

 **To Insert Value In Table**           
  `insert t1 values("name",20);` 	
  
 **To Show Tables**.      
  `show tables;`	

 **To Delete All Stored Data In Table**	                       	
   `delete from t1;`   

 **To Delete Table**               
   `drop table  t1, t2;`	

 **To Add New Column In Table**             
   `alter table t1 add Column-Name char(20);`

 **To Delete Column In Table**	             	   
   `alter table t1 drop Column-Name;`		


<h3>Advance Commmands Mysql</h3>
`set password for user@localhost=password('password');` **TO SET OR RESET PASSWORD
`commit;`						**TO MAKE CHANGES PUBLICLY OF DATABASE'S DATA
`update t1 SET name='test' where age=20;              ` **TO CHANGE DATA IN COLUMN

**Some Operation Mysql**
* Union - Operation to fetch common output between two queries. but the number of columns and the data type of column's must be same to the both side of UNION
  `select name,age from t1 union select nickname, id from t2;`






   




					
