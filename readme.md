`docker run --rm -v $(pwd):/app composer install`  

`cp .env.example .env`  

`docker-compose exec app php artisan key:generate`  

`docker-compose up`  

Enter on http://localhost
