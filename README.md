# Laravel 4 w/ Vagrant

## Tasks:

 * create laravel project wiht composer
 * update app key for sake of security
 * add empty README.md
 * set local timezone
 * Install useful packages for Laravel dev
   * way/generators https://github.com/JeffreyWay/Laravel-4-Generators
   * itsgoingd/clockwork https://github.com/itsgoingd/clockwork
   * fzaninotto/faker https://github.com/fzaninotto/Faker
   * phpunit/phpunit https://github.com/sebastianbergmann/phpunit
 * set aliases and service providers
 * set clockwork files in app/start/local.php
   * now you can debug you app by using console logs by typing: l('log this')
 * create laravel local env files and settings 
 * crate mysql database and set laravel db config
 * set apache user and group to vagrant so it can rw to app/storage
 * set up apache vhost for vagrant folder, so you can access the server as: 192.168.33.10.xip.io
 * to use SauceLab connect to test your local instance edit your host file
 127.0.0.1 192.168.33.10
