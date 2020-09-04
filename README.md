# sample-databases

Restore on linux
chmod 777 .
RESTORE DATABASE [AdventureWorks] FROM DISK = '/home/<username>/sample-databases/sql-server/AdventureWorks2019.bak' WITH MOVE 'AdventureWorks2017' TO '/var/opt/mssql/data/AdventureWorks.mdf',  MOVE 'AdventureWorks2017_log' TO '/var/opt/mssql/log/AdventureWorks.ldf'
