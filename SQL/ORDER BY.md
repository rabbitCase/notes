- Sort data by specifying column(s)
- Add ASC/DESC after the column to sort ascending/descending
- Default sorting is ascending
```
SELECT * 
FROM customers 
ORDER BY CustomerId DESC;

SELECT * 
FROM customers 
ORDER BY City; (Alphabetical sorting)

SELECT * 
FROM customers 
ORDER BY City DESC;

SELECT * 
FROM invoices 
ORDER BY BillingCity ASC, InvoiceDate DESC;
```