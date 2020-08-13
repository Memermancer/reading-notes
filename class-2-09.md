**SQL Bolt 5-8
Good practice, now that we've used SQL in a lab I understand it better. Order by should prove useful. Joins are a little much but seem super cool. Right and left join are the weirdest to me, the other joins, and the difference between inner and outer joins, is pretty clear to me. Nulls are something to watch out for in SQL.

**Intro to Database Normalization
This describes the process to organize a database into tables that are focused on a specific topic and supporting topics. Better to have another database than a bloated database. This simplifies queries and lowers the risks of creating anomalies or having redundant data. The three normal forms of database normalization are:
First: The info is stored in a table with each column containing atomic values, with no repeating columns.
Second:The table has first form normalization and the columns depend on the table's key.
Third: First and second forms plus the columns are not transitively dependant on the key from second form.

**Visual Representation of SQL Joins
Happy to see a visual aid for joins because they were somewhat opaque. This helps a great deal to understand what data we are going to get when we perform a join. It also shows how easy it is to create a null value when joining anything except inner.