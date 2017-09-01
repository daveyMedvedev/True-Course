To load this project you will need:

Apache2 or Xampp
PGSQL
PHP

Simply replace the www(project working directory) with /var/www directory or extract the files into it.
Start up your local server and the project will be deployed.

To recreate the database in pgsql, use pg_restore to open the backup.

Command: 
$ pg_restore -d postgres truecoursedbback