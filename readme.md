# Adding custom fields to Laravel Passport authentication

This example project shows a way to add custom fields to Laravel Passport password grant authentication. In order to achieve this, some laravel/framework and laravel/passport methods are overrided in the following classes: 

- App\User
- Illuminate\Auth\EloquentUserProvider
- Laravel\Passport\PassportServiceProvider
- Laravel\Passport\Bridge\UserRepository
- League\OAuth2\Server\Grant\PasswordGrant
- App\AuthServiceProvider 

The custom Passport files are placed inside app/Extensions.
