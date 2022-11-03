# SQL_Query
 <H2>Link : https://www.sqltutorial.org/ </H2>
 
 <H2>JOIN</H2>
 SQL JOIN : 
 
 SELECT b.id,b.branch_name,
f.id,f.fee_category
FROM branch AS b
JOIN feecategory AS f
ON b.id=f.id;
First Print From Table :

<BR>
RIGHT JOIN : 

SELECT b.id,b.branch_name, f.id,f.fee_category 
FROM branch AS b 
RIGHT JOIN feecategory AS f 
ON b.id=f.id;

<BR>
LEFT JOIN :

SELECT b.id,b.branch_name, 
f.id,f.fee_category 
FROM branch AS b 
LEFT JOIN feecategory AS f
ON b.id=f.id;

<BR>
CROSS JOIN :

SELECT b.id,b.branch_name,
f.id,f.fee_category 
FROM branch AS b 
CROSS JOIN feecategory AS f 
ON b.id=f.id;

<BR>
FULL JOIN : 

SELECT b.id,b.branch_name,
f.id,f.fee_category
FROM branch AS b 
FULL JOIN feecategory AS f 
ON b.id=f.id;




SELECT * FROM branch ORDER BY ID LIMIT 5;

Last Print Form Table :

SELECT * FROM branch ORDER BY ID DESC LIMIT 5;


Link : https://www.sqltutorial.org/sql-limit/
