- Compare records, add condition using WHERE clause and comparison operators
```
SELECT name,course_id
FROM instructor,teaches
WHERE (Intructor_id, dept_name) = (teaches_id, 'Biology');
```