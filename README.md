# Laravel Bulgarian Language

Bulgarian lang translations for [Laravel 6](https://laravel.com).

## Install

1. First clone the [GitHub repo](https://github.com/PIPONCHOV/laravel-lang-bg/) with: 
`git clone https://github.com/PIPONCHOV/laravel-lang-bg.git` or download the [zip file](https://github.com/PIPONCHOV/laravel-lang-bg/archive/master.zip)
2. Copy the `src/bg` folder from this repo into `resources/lang` folder of your Laravel application.


## Usage

By default language strings are stored in files within the Laravel's `resources/lang` directory. Within this directory there you should create subdirectory for each new language supported by the application:

```
/resources
    /lang
        /en
            auth.php
            pagination.php
            passwords.php
            validation.php
        /bg
            auth.php
            pagination.php
            passwords.php
            validation.php
```

## Default language

If you want to set bulgarian as a default language in your application you just have to edit `config/app.php` and change the value from `'locale' => 'en',` to `'locale' => 'bg',`.
