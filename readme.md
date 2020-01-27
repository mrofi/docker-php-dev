## PHP & Laravel Development Environment
This package include :
- PHP 7.2
- Mysql Database
- Nginx Proxy

## How To
- clone this repository :
```shell
git clone git@github.com:mrofi/docker-php-dev.git
```

- clone any laravel / php project in folder ./www/ 

## What next ?
Access your project in browser with this url :
```shell
http://{folder_name}.localhost
```

## CLi support
This only support when you are in your project folder
- Sql :
```shell
dsql create database osas_db
```

- Mysql (To import DB)
```shell
dmysql osas_db < my_backup_2012xxx.sql
```

- Bash / PHP Command
```shell
dexec php artisan route:list
```

