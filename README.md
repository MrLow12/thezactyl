# thezactyl theme pterodactyl by zakkiXD-Dev 

<div align=center>

## 1 command simple install 
## install theme ini setelah kalian install panel dan wings !!!

```sh
cd /var/www/pterodactyl && php artisan down && curl -L -o thezactyl.tar.gz https://github.com/MrLow12/thezactyl/releases/download/latest/thezactyl.tar.gz && tar -xzvf thezactyl.tar.gz && rm -f thezactyl.tar.gz && chmod -R 755 storage/ bootstrap/cache && composer require asbiin/laravel-webauthn -y && composer install --no-dev --optimize-autoloader -y && php artisan optimize:clear && php artisan migrate --seed --force -y && chown -R www-data:www-data /var/www/pterodactyl/* && php artisan queue:restart && php artisan up
```
