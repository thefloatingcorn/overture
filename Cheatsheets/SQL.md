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




## Default

SELECT * FROM myTable ORDER BY x DESC LIMIT 5 OFFSET 10

SELECT * FROM myTable WHERE a LIKE '"\_s%"' and
SELECT * FROM myTable WHERE a = "" or b IN ()
SELECT b FROM myTable WHERE c IS NOT NULL AS d

UPDATE SET WHERE
SELECT COUNT (DISTINCT a, b)
DELETE FROM  
DROP TABLE IF EXISTS myTable
DROP TABLE IF EXISTS myTable


CREATE TABLE myTable ( a INTEGER, b TEXT, c TEXT );

UNIQUE
DEFAULT 'panda'

INSERT INTO myTable VALUES (1, 2)

QUOTES?
