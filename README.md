<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>



## Packages


- composer require stevebauman/location
- In config/app.php file add this ->

'providers' => [

	....

	Stevebauman\Location\LocationServiceProvider::class,

],

'aliases' => [

	....

	'Location' => 'Stevebauman\Location\Facades\Location',

]

- php artisan vendor:publish

## Output



<p align="center">
<img src="https://user-images.githubusercontent.com/80118217/195654009-d9a3a296-1cf0-425f-9d21-c99ab99e214b.JPG">
</p>


