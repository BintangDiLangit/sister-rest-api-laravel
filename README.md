# API BASIC

this repository provide API to BASIC application, the entire application is made by using laravel 8

## Requirements

-   composer 2.x
-   laravel 8
-   php >= 7.4

## Installation

-   first clone this repo

```bash
$ git clone https://github.com/BintangDiLangit/sister-rest-api-laravel.git
```

-   go into the project directory

```bash
$ cd sister-rest-api-laravel
```

-   then install the laravel

```bash
$ composer install
```

-   after that copy the `.env.example` file and update it using your database credentials

```bash
$ cp .env.example .env
```

-   do artisan migrate

```bash
$ php artisan migrate --seed
```

-   lastly serve your server

```bash
$ php artisan serve
```
