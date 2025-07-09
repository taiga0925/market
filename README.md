#環境構築
1. git clone git@github.com:coachtech-material/laravel-docker-template.git
2.  mv laravel-docker-template marekt
3.  docker-compose up -d --build
4.  docker-compose exec php bash
5.  composer install
6.  cp .env.example .env
7.  .env ファイル修正
8.  php artisan key:generate
9.  php artisan storage:link
10.  composer require stripe/stripe-php
11.  composer require guzzlehttp/guzzle
