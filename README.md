<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## ADDRESSING 3 DEADLY SINS IN WEB DEVELOPMENT

1.) Hardcoding queries
<br>
    Can be seen in app/Http/Controllers/Auth/RegisterController.php line 68
<br>
2.) Using context-independent cookies
<br>
    Remember me token is context-dependent. Can be seen in DB where the token is hashed and is dependent to the user
<br>
3.) Using magic/hidden inputs in forms and accessing them
<br>
    Both the login and registration form don't use hidden inputs except csrf tokens which is unique to each forms and can only be used once.
<br>
## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
