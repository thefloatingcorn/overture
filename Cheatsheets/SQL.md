# SQL

http://www.runoob.com/sql/sql-quickref.html

Statement | Syntax
---|---
SELECT | SELECT column_name(s) FROM table_name
SELECT * | SELECT * FROM table_name
SELECT DISTINCT	| SELECT DISTINCT column_name(s) FROM table_name
WHERE	| SELECT column_name(s) FROM table_name WHERE column_name operator value
INNER/LEFT/RIGHT/FULL JOIN | SELECT column_name(s) FROM table_name1 INNER JOIN table_name2 ON table_name1.column_name=table_name2.column_name
HAVING | SELECT column_name, aggregate_function(column_name) FROM table_name WHERE column_name operator value GROUP BY column_name HAVING aggregate_function(column_name) operator value
CREATE INDEX | CREATE INDEX index_name ON table_name (column_name)
