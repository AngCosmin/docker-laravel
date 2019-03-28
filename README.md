#### 1. Composer install
On Linux/MacOS: `docker run --rm -v $(pwd):/app composer install`  
On Windows in PowerShell: `docker run --rm -v ${PWD}:/app composer install`  
On Windows in CMD: `docker run --rm -v %cd%:/app composer install`  

#### 2. Create .env file
`cp .env.example .env`  

#### 3. Start everything
`docker-compose up`  

#### 4. Generate key for Laravel application
`docker-compose exec app php artisan key:generate`  

#### 5. Profit
Enter on http://localhost
