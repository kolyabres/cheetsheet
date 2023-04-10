# cheetsheet

## mysql dump

```
mysqldump -u [user name] –p [database_name] [tablename] > dumpfilename.sql
```

## download via ssh

```
scp your_username@remotehost.edu:foobar.txt /local/dir

with pem file
scp -i key_file.pem your_username@remotehost.edu:/remote/dir/foobar.txt /local/dir
```

## ssh keygen
`ssh-keygen -t ed25519 -C "your_email@example.com"`


## macos php versions
https://www.markhesketh.com/switching-multiple-php-versions-on-macos/

```
 brew list | grep php

brew tap shivammathur/php
brew install shivammathur/php/php@7.4


brew unlink php@5.6
brew link php@7.4 --force
```

