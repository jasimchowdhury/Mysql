Mysql

To start the system:
sudo systemctl status mysql.service





Data Types: that can be used in mysql in relational data base.
	1: INT – 			-- whole number
	2: DECIMAL (M,N)		-- Decimal numbers – exact value
	3: VARCHAR (1)		-- String of text of length 1
	4: BLOB			-- Binary large object, stores large data
	5: DATE			-- “YYYY-MM-DD”
	6: TIMESTAMP		-- ‘YYYY-MM-DD  HH:MM:SS’


1. CREATE TABLE:
	*CREATE TABLE table name (
		column name DATATYPE PRIMARY KEY,
		second column name VARCHAR(20),
		third column name VARCHAR(20),
	);
	
2. Describe table:
	* DESCRIBE table name;

3. Drop table:
	*DROP TABLE tablename;

4. Insert data to first column
	ALTER TABLE tablename ADD gpa DECIMAL(2,3);

5. Drop column from the table
	ALTER TABLE tablename DROP COLUMN column name;

6. SELECT * FROM tablename; (will give all the information from the table)

7. Insert values into the table
	INSERT INTO tablename VALUES(1, ‘string’, ‘string’);

8. Insert values into the table if the other values are not available:

	INSERT INTO tablename(columnname, columnname) VALUES(values, values);

9. NOT NULL, UNIQUE, UNDECIDED, AUTO_INCREMENT