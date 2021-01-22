## Spatie Permission Package Installation

1) Composer require spatie/laravel-permission
2) In config/app.php file:
 	'providers' => [ // ...
  		  Spatie\Permission\PermissionServiceProvider::class, ];
3) php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider"
4) php artisan migrate