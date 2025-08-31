| setup laravel+docker+mysql+nginx+redis |


git clone https://github.com/itowaka044/setupsetupsetup


cd setupsetupsetup


cp .env.example .env


docker-compose up -d


docker-compose exec app bash


composer install


php artisan key:generate


php artisan migrate


npm install


npm run dev
