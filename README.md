# socialmeter

## Create Database

```
mysql -u root -p
```
```
GRANT ALL PRIVILEGES ON *.* TO 'socialmater'@'localhost' IDENTIFIED BY 'socialmater'; quit;
```
```
mysql -u socialmater -p
```
```
CREATE DATABASE socialmater; quit;
```

## Setup Environment


## Migrate Database

### Migrate Voyager
```
php artisan voyager:install --with-dummy
```