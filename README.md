n first step, we need install jorenvanhocht/laravel-share composer package so let's use bellow command to install:

composer require jorenvanhocht/laravel-share
after installing successfully, we need to publish configuration file using bellow command:

php artisan vendor:publish --provider="Jorenvh\Share\Providers\ShareServiceProvider"
