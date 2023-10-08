# API_SYMFONY_TRAINNIG
TODO

clone repository before start
```bash
git clone https://github.com/soo-essoklina-ulrich/API_SYMFONY_TRAINNIG.git
```
Move to the project folder
```bash
cd API_SYMFONY_TRAINNIG
```
Install dependencies
```bash
composer install
```
##
### Database configuration
in .env file, change the following line if you are using mysql
```bash
DATABASE_URL=mysql://db_user:db_password@db_host:db_port/db_name
```

Create database
```bash
php bin/console doctrine:database:create
```
Create tables
```bash
php bin/console doctrine:schema:update --force
```
##
### Server

Run server
```bash
php -S localhost:8000 -t public
```
