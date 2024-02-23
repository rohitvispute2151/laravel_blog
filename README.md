

## Installation

First clone this repository, install the dependencies, and setup your .env file.

```
git clone https://github.com/rohitvispute2151/laravel_blog.git
composer install
cp .env.example .env
```

Then create the necessary database.

```
create a new database `blog` using Mysql
```

And run the initial migrations and seeders.

```
php artisan migrate --seed
```

And then serve the project with 

```
php artisan serve
```