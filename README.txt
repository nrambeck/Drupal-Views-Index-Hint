Views Index Hint

DESCRIPTION
Allows MySQL Index Hint syntax to be added to Views queries. Using an index
hint is one solution for poorly performing queries, usually on large
datasets, in which the MySQL optimizer refuses to choose the most
appropriate index. For more information on index hints check out the
documentation:
http://dev.mysql.com/doc/refman/5.1/en/index-hints.html

REQUIREMENTS
Index hints only work the the MySQL database

USAGE
To add an index hint to a Views query, simply enable the module, then
navigate to the view you would like to add the index hint to. You should see
a new option in the General section called "Index Hint." Simply click to
edit this field and add your index hint using the proper syntax.

