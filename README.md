# PostgreSQL-queries
<br>
## Saving/Exporting results of a database query to a simple text file.
By default all query results are displayed on the screen. This default behavior can be overwritten by \o command:
postresql=> \o /path/to/your/text/file.txt
postresql=> postgresql query ( here place your query ) 
postresql=> \o ( set back the default output behavior )
