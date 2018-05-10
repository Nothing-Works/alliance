# alliance
<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>


## Features


Tasks management
Leads management
Simple invoice management
Easy & simple time management for each task
Role management (Create and update your own roles)
Easy configurable settings
Client overview (Keep easy track of open tasks for each client etc)
Upload documents to each clients (easy track of contracts and more)
Fast overview over your own open tasks, leads etc
Global dashboard
To-do
Flarepoint is still under development, so there are a lot on my to-do list.

Multiple integrations (Slack, e-conomic, Google Drive, dropbox etc.)
Different Color schemes
API
Excel Import/export
Better cache
Even easier installation

## Installation
1.Clone from git

2. to create your own version of all the environment variables needed for the project to work.
 
```
cp .env.example .env 
```


3. Update ` .env `to your specific needs. Don't forget to set `DB_USERNAME` and `DB_PASSWORD` with the settings used behind.

4. Run `composer install --no-interaction --prefer-dist --no-suggest --optimize-autoloader --no-dev` to install all packages.

5. Run `php artisan key:generate` to generate an application key. This will set APP_KEY with the right value automatically.

6. Run `php artisan migrate`

7. Run `php artisan setup:production` to run the migrations, seed the database and symlink folders.

8. Optional: run `php artisan passport:install` to create the access tokens required for the API (Optional).

9. Optional: it may requires some background processes to continuously run. The list of things it does in the background is described here. To do this, setup a cron that runs every minute and triggers the following command `php artisan schedule:run`.

10. You are good to go

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, yet powerful, providing tools needed for large, robust applications. A superb combination of simplicity, elegance, and innovation give you tools you need to build any application with which you are tasked.

## Learning Laravel

Laravel has the most extensive and thorough documentation and video tutorial library of any modern web application framework. The [Laravel documentation](https://laravel.com/docs) is thorough, complete, and makes it a breeze to get started learning the framework.

If you're not in the mood to read, [Laracasts](https://laracasts.com) contains over 900 video tutorials on a range of topics including Laravel, modern PHP, unit testing, JavaScript, and more. Boost the skill level of yourself and your entire team by digging into our comprehensive video library.

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](http://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell at taylor@laravel.com. All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
