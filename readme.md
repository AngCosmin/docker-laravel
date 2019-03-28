On Linux/MacOS:
`docker run --rm -v $(pwd):/app composer install`  

On Windows:
`docker run --rm -v ${PWD}:/app composer install`  

`cp .env.example .env`  

`docker-compose up`  

`docker-compose exec app php artisan key:generate`  

Enter on http://localhost
