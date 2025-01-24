- Perform mathematical set operations like union, intersection, difference
```
(
SELECT course_id 
FROM section
WHERE sem= 'Fall' AND year=2009
)
UNION/INTERSECT/EXCEPT/MINUS
(
SELECT course_id 
FROM section
WHERE sem= 'Spring' AND year=2010
)
```