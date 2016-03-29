# backup-creator

Overview
--------

This ant script will do a zip backup of a given folder. Date and time will be automatically added to the final zip file name. 

Parameters
----------

- src.dir - Folder to backup.
- dest.dir - Folder where to save backup zip file.
- base-name - Backup zip file name without extension & date/time.

Example usage
-------------

	ant -Dsrc.dir=example/foobar -Ddest.dir=backup -Dbase-name=foobar
