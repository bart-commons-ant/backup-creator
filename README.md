# backup-creator

Overview
--------

Creates zipped backup of a given folder. Date and time will be automatically added to the final zip file name. 

Parameters
----------

- src.dir - Folder to backup.
- dest.dir - Folder where backup zip file will be saved (will be created if not already exist).
- base-name - Backup zip file name without extension & date/time.

Example usage
-------------

	ant -Dsrc.dir=example/foobar -Ddest.dir=backup -Dbase-name=foobar
