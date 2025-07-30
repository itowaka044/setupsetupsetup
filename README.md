| SETUP Laravel |


git clone https://github.com/itowaka044/laravel-docker-mysql-tailwind-bootstrap.git


cd laravel-docker-mysql-tailwind-bootstrap


cp .env.example .env


docker-compose up -d


docker-compose exec app bash


composer install


php artisan key:generate


php artisan migrate


npm install


npm run dev
