# LaraFlat
Advanced laravel system to build admin panel 


## Download The Files 

download all files

## Install with Composer

```
composer create-project laraflat/laraflat  --prefer-dist  ProjectName --stability=dev
```

## Requirements

PHP >= 5.6.4 , 
PHP Curl extension <br>
You Must check if you have 

```
extension=php_zip.dll
```
And Enable in php first

## Install  The Dependencies

now type this line on your console

```
php artisan key:generate
```

## Migrate

```
  php artisan migrate
```

## Seed Database 

```
  php artisan db:seed
```

## Start Server


```
  php artisan serve
```

## Login

```
  email : admin@gmail.com
  pass : admin
```

## Go To Admin Path

```
  http://127.0.0.1:8000/admin/home
```

## Add New Model

```
    php artisan make:admin_model NameOfModel
```


