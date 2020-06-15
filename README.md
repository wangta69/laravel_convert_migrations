## INSTALL
upLoad ConvertMigrations to App\Http\Controllers

modify app/Console/Kernel.php
protected $commands = [
 'App\Http\Controllers\ConvertMigrations\ConvertMigrationsCommand',
];

php artisan convert:migrations YourDataBaseName
