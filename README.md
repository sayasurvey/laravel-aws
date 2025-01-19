# AWSにデプロイ検証するための環境
LaravelのHello World画面まで

## 参考サイト
https://www.chickensblog.com/docker-nginx-php81-laravel9/

## サーバー起動
docker compose exec app bash
php artisan serve --host=0.0.0.0 --port=8080