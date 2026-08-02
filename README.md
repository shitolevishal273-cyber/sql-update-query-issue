# SQL Update Query Issue

## Problem

I am trying to update a student's record in MySQL.

### SQL Query

```sql
UPDATE STUDENT_INFO
SET
    STUDENT_ID = 1003,
    NAME = 'ANIL SHITOLE',
    GENDER = 'MALE',
    DOB = '1974-01-01',
    COLLEGE = '--'
WHERE EMAIL = 'ANILSHITOLE@GMAIL.COM';
```

### Error

```
Error Code: 1054
Unknown column 'EMAIL' in 'where clause'
```

### Expected Result

The record should be updated successfully.

### Need Help

- Why am I get this error?
- How can I find the correct column name?
- What is the correct SQL query?
