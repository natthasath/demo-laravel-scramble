# 🎉 DEMO Laravel Scramble

Laravel Scramble is a package that generates random strings to obfuscate data for testing or security purposes. It offers customizable length and character sets to suit various needs. Ideal for protecting sensitive information or creating dummy data in Laravel applications.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### 🚀 Setup

- Create Project

```shell
composer create-project laravel/laravel example-app
```

- Install Package

```shell
composer require dedoc/scramble
```

- Configure Environment

```shell
cp .env.example .env
```

- Vendor Publish

```shell
php artisan vendor:publish --provider="Dedoc\Scramble\ScrambleServiceProvider" --tag="scramble-config"
```

- Migrate

```
php artisan migrate --seed
```

### 🏆 Run

- [http://localhost:8000/docs/api](http://localhost:8000/docs/api) username : `admin` password : `admin`

```shell
php artisan serve
```
