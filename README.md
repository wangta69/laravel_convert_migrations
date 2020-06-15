## INSTALL
### UPLOAD
upLoad ConvertMigrations to App\Http\Controllers

### MODIFY
modify app/Console/Kernel.php
protected $commands = [
 'App\Http\Controllers\ConvertMigrations\ConvertMigrationsCommand',
];

### Command on Console
php artisan convert:migrations YourDataBaseName
