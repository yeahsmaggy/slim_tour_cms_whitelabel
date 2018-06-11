# Slim Tour CMS
CMS for Tour Company built with SLIM Microframework.

I've only just stripped this back to Whitelabel so its not tested. It needs some TLC.

The database isn't include please contact me on montane@protonmail.com.


## Reqs

- Mysql 5+ 
- PHP 7+
- npm
- composer

### Deployment

- Ruby
- Capistrano

## Install

- clone this repo
- cd into directory

```bash
composer install
```

- import the database file

```bash
mysql -uroot slimtest < /Users/User1/vprojects/Slim-Tour-CMS/migrations/slimtest.sql
```

## Development

```bash
php -S localhost:8888 -t public
```
