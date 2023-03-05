## How to use ?

 1.  clone this repo
 2.  create .env (duplicate from .env-example)
 3.  setup database
		    **DB_CONNECTION=mysql
		    DB_HOST=127.0.0.1
		    DB_PORT=3306
		    DB_DATABASE=your database
		    DB_USERNAME=root
		    DB_PASSWORD= your password**
		  
 4.  install dependency php `composer install` 
 5.  install dependency node js `npm install`
 6.  generate key `php artisan key:generate`
 7.  migrate database `php artisan migrate`
 8.  run project `php artisan serve`