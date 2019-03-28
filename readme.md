`docker run --rm -v $(pwd):/app composer install`  

`cp .env.example .env`  

`docker-compose up`  

`docker-compose exec app php artisan key:generate`  

Enter on http://localhost
