acquia_db
=========

A shell script to get the db credentials for a database and environment on Acquia's hosting platform.

The script outputs a connection string suitable for use with the mysql or mysqldump command line tools. 

Use it like this:

$ mysql `aq_db my_database dev`
$ mysqldump `aq_db my_database test` < sql_dump.sql
