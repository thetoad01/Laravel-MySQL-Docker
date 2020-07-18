# Laravel-Mysql-Docker
Docker setup for Laravel includes MySQL container.

## Docker Basics
To run project:  
```
docker-compose up -d --build
```

Make sure you are in the src/ directory when running Composer commands.  

To run Artisan commands:  
```
docker-compose exec php php /var/www/html/artisan COMMAND
```

Site available at:  
```
localhost:8088
```
