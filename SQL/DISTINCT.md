- Keeps only unique values
 - When only one column or expression is provided in the DISTINCT clause, the query will return the unique values for that column. 
- When more than one column or expression is provided in the DISTINCT clause, the query will retrieve unique combinations for those columns. 
- The DISTINCT clause doesn't ignore NULL values in DISTINCT column(s). NULL values are considered as unique values by DISTINCT.
- Examples:
```
SELECT BillingCountry  
FROM invoices 
ORDER BY BillingCountry;
```
![[Pasted image 20250114225201.png]]
```
SELECT DISTINCT BillingCountry, BillingCity   
FROM invoices 
ORDER BY BillingCountry, BillingCity;
```
![[Pasted image 20250114225251.png]]
- Can also be used with SQL aggregate functions
```
SELECT COUNT(DISTINCT country)  
FROM customers;
```