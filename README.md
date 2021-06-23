# Secure-REST-API
How to create REST API in PHP

## To quickly install Composer

    php -r "copy ('https://getcomposer.org/installer', 'composer-setup.php');"
    php composer-setup.php
    php -r "unlink ('composer-setup.php');"
    
## Configure composer 

    php composer.phar init

        Define your dependencies.

        Would you like to define your dependencies (require) interactively [yes]?
        Search for a package: vlucas/phpdotenv
        Enter the version constraint to require (or leave blank to use the latest version): ^2.4

## And some update for composer
    
    php composer.phar update
    composer self-update