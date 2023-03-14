# Minhas configurações e dicas

Aqui funcionou bem assim:

composer install

cp .env.example .env

Configurei .env

php artisan migrate

php artisan db:seed --class=PermissionTableSeeder

php artisan db:seed --class=CreateAdminUserSeeder

Rodei os dois seeders:

php artisan serve

http://127.0.0.1:8000/login

syed@test.com
password123
