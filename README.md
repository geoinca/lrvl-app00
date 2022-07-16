# lrvl-app00
Laravel
+++++++++
https://www.purocodigo.net/articulo/como-configurar-laravel-nginx-y-mysql-con-docker-compose 
+++++++++
Run 
docker-compose up -d

docker-compose exec app php artisan key:generate
docker-compose exec app composer require  barryvdh/laravel-debugbar --dev

docker-compose exec app composer require laravel/jetstream


docker-compose exec app php artisan jetstream:install livewire

docker-compose exec app npm install && npm run dev

docker-compose exec app php artisan migrate:refresh --seed 