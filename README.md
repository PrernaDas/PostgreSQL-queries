# PostgreSQL-queries
<br>
## Saving/Exporting results of a database query to a simple text file.
<br>
By default all query results are displayed on the screen. This default behavior can be overwritten by \o command:
<br>
postresql=> \o /path/to/your/text/file.txt
<br>
postresql=> postgresql query ( here place your query ) 
<br>
postresql=> \o ( set back the default output behavior )
