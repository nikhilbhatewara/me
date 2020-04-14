# SQL

 - The DUAL table (1x1) is a special table in Oracle which can be leveraged as sequence generator or selecting pseudo fields such as SYSDATE. 
 - MySQL has a 1x1 dual table with dummy as field name
 - SQL Server does not have dual table.
 - We can insert more rows in dual table with admin access.
 - We cannot download all columns from a table #rookiemistake
 - count(1),count(*) provides same results using same resources
 - An IN operator can only take upto 999 values
 - **IN vs EXISTS:** When IN is used, *inner query will be executed first* and then outer query. When EXISTS is used, the *outer query is executed first* and then based on number of records form outer query, the inner query is executed. 
 - EXISTS operator works based on the “at least found” principle. It returns true and stops scanning table once at least one matching row found. Hence it is good to check if query would give any result or not
 - **WHERE vs HAVING:** Where is used to filter data *before aggregation* and Having is used to filter data *after aggregation*
