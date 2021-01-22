## Spatie Permission Package Installation

1) Composer require spatie/laravel-permission
2) In config/app.php file:
 	'providers' => [ // ...
  		  Spatie\Permission\PermissionServiceProvider::class, ];
3) php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider"
4) php artisan migrate


## Yajra datatables

1) Make Auth UI
2) Make Dummy data entry and fetch it in table form
    php artisan Tinker
    App\Models\User::factory(100)->Create();
3) composer require yajra/laravel-datatables:^1.0    --(1.2 if 1.0 doesnt work)
4) php artisan vendor:publish --tag=datatables

