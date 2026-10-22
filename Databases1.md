# Databases1

SQL = Standard language for querying and manipulating data = Structured Query Language, it's for querying and manipulating data
SELECT shop
FROM located
WHERE area = 'west'  - strings have quotes '

Logical operators 
AND Both conditions must be
true
OR At least one condition must
be true
NOT Reverses a condition

List / pattern predicates
IN / NOT IN In (or outside) a
value list
LIKE Matches a text
pattern
NOT LIKE Does not match the
pattern

No, it is not picking a random shop—it is asking for all unique combinations of shop and Area in the table.   Here is why:SELECT shop, Area asks the database to show all shops and their areas.   DISTINCT tells the database: "Show me every pair, but don't show the exact same combination more than once."

. The Equals Sign = Matches Rows Across Tables
The equals sign in WHERE made_of = material tells SQL how to connect matching records between those two tables.
