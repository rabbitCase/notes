- Perform arithmetic operations like +, -, /, *, % on tables
- Take the table for example
- ![[Pasted image 20250114211751.png]]
- ![[Pasted image 20250114211833.png]]
- We can perform various operations on them
`SELECT salary + allowance FROM employee;` would give:
- ![[Pasted image 20250114211946.png]]
```
SELECT * 
FROM employee 
WHERE salary + allowance = 25000;
```
gives:
- ![[Pasted image 20250114212036.png]]
- Similarly we can perform multiple operations like:
```
SELECT salary - tax FROM employee;

SELECT * 
FROM employee 
WHERE salary - tax = 50000;


SELECT *  
FROM employee 
WHERE tax * 2 = 4000;


SELECT allowance / salary * 100 FROM employee;

SELECT *  
FROM employee 
WHERE allowance / salary * 100 >= 5;
```
- ![[Pasted image 20250114212353.png]]
```
SELECT hours % 2 FROM employee;

SELECT * 
FROM employee 
WHERE hours % 2 = 0;
```