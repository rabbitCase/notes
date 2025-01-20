- Take column from the source table and transfer it into destination table
```
INSERT INTO target_table(column_name)
SELECT column_name
FROM source_table;
```