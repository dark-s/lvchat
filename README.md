# Chat app on Laravel PHP Framework and Vue.js

### Instalation

* Create database
* Clone project:
```sh
$ git clone https://github.com/dark-s/lvchat.git
```
* Create and config ***.env*** file
* Install composer packages:
```sh
$ composer install
```
* Install npm packages:
```sh
$ npm install
```
* Generate unique key:
```sh
$ php artisan key:generate
```
* Create necessary tables:
```sh
$ php artisan migrate
```
or restore from file /database/lvchat.sql
* Add users:
```sh
$ php artisan db:seed --class=SentinelDatabaseSeeder
```
