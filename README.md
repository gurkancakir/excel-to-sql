# excel-to-sql

## How works
1) upload excel file.
2) write sql template
3) convert sql file

## Example SQL

```sql

UPDATE TEST.TEST_TABLE T
   SET T.COLUMN_1 = #0#, -- 1.column
       T.COLUMN_2 = #1#  -- 2.column
 WHERE T.COLUMN_3 > 0

```
