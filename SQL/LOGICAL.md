- ![[Pasted image 20250114223507.png]]
- Examples
```
SELECT *   
FROM invoices  
WHERE Total > 2;


SELECT column1, column2, columnN  
FROM table_name 
WHERE [condition1] AND [condition2]...AND [conditionN];

SELECT *  
FROM invoices 
WHERE Total > 2 AND BillingCountry = 'USA';


SELECT *  
FROM invoices 
WHERE BillingCountry = 'USA' OR BillingCountry='France';


SELECT *  
FROM invoices  
WHERE Total > 2 AND (BillingCountry = 'USA' OR BillingCountry = 'France');
```