# Laravel 7 create word document with PHPOffice/PHPWord

# Installation
1. Clone this repo
```
https://github.com/samironbarai/laravel-7-word-document.git
```

2. Install composer packages
```
cd laravel-7-word-document
$ composer install
```

3. Create and setup .env file
```
make a copy of .env.example and rename to .env
$ php artisan key:generate
put database credentials in .env file
```

4. Migrate and insert records
```
$ php artisan migrate
$ php artisan tinker
$ factory(App\User::class, 50)->create()
```

See the video tutorial

[![](https://img.youtube.com/vi/15WXlDO_F20/0.jpg)](https://www.youtube.com/watch?v=15WXlDO_F20) 
