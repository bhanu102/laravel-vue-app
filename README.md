Building Laravel Vuejs CRUD Single Page Application

composer create-project laravel/laravel laravel-vue-crud --prefer-dist
php artisan make:model Product -m
php artisan migrate
php artisan make:controller ProductController
composer require laravel/ui
php artisan ui vue
npm install vue-router vue-axios
npm install
npm run watch
php artisan serve
http://127.0.0.1:8000