## master-laravel

### Autoload gagal 
Apabila terjadi error 
 > Warning: require(C:\xampp\htdocs\master-laravel-master/vendor/autoload.php): failed to open stream: No such file or directory in C:\xampp\htdocs\master-laravel-master\index.php on line 24
 
Jalankan sintaks berikut pada terminal powershell
 > composer install 
 
 > cp .env.example .env
 
 > php artisan key:generate