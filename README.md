<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel Chirper is a chatting web application that built with Laravel, I built this app while I was taking the Laravel bootcamp.
https://bootcamp.laravel.com/blade/installation

## Installation

First clone the repository. 
```sh

git clone https://github.com/mahmoud-x923/laravel-chirper.git
```
Then install dependencies.
```sh

composer install
```

Setup your .env file.
```sh

cp .env.example .env
```

Next step is to create the database.
```sh
php artisan db
create database {DB_NAME}
```

Finally, run the migration and seeders
```sh
php artisan migrate --seed
```

