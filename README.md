# cheetsheet

## mysql dump

```
mysqldump –p -u [user name]   [database_name] [tablename] > dumpfilename.sql
```

## download via ssh

```
scp your_username@remotehost.edu:foobar.txt /local/dir

with pem file
scp -i key_file.pem your_username@remotehost.edu:/remote/dir/foobar.txt /local/dir
```
