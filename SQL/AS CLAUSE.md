- Find names of all instructors who have a higher salary than some instructor in CSE branch. We can use the AS clause in this case
```
SELECT T.name
FROM instructor as T, instructor AS S
WHERE T.salary > S.salary AND S.dept_name= 'comp_sci';
```