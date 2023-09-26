# Laravel MongoDB Passport Fix
This is a code snippet that will update the `Illuminate\Database\Eloquent\Model` models in the Passport vendor to include `MongoDB\Laravel\Eloquent\Model`.

## Installation
- Create a console command by running: `php artisan make:command MongoDBPassportFix`
- It will create the file `MongoDBPassportFix` and you can locate it under `app/Console/Commands`
- Just copy/paste the content from `MongoDBPassportFix.php` to the command you just generated.

## Run the fix
- Just do `php artisan fix:passport` and it will do a scan and update it.

## Revert changes
- If you want to revert, just do: `php artisan fix:passport --rollback`.

> Note:
This will need to be run every time Laravel Passport is updated.
