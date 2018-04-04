# Métier du Numérique

## Description

Présentation des métiers du numérique.

## Steps

1. Clone the repos from Github.
2. Run `composer install`.
3. Create *app/db.php* from *app/db.php.dist* file and add your DB parameters.
```php
define('APP_DB_HOST', 'your_db_host');
define('APP_DB_NAME', 'your_db_name');
define('APP_DB_USER', 'your_db_user_wich_is_not_root');
define('APP_DB_PWD', 'your_db_password');
```
4. Go to public/ directory and run a server on index.php with `php -S localhost:8000`.
5. Test on your localhost default URL : `localhost:8000`.
6. From this starter kit, create your own web application.
