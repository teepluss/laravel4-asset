A port of Laravel 3's Asset class. Made to work with Laravel 4.


## Usage

### Composer Side

add `"teepluss/asset": "dev-master"` to the `require` section of your `composer.json` so that it should look something the code below.

```composer
...
...
...
"require": {
	...
	...
	...
	"teepluss/asset": "dev-master"
},
...
...
...
```

### Laravel Side

add the following code to the `providers` section of the `app/config/app.php` file

```php
'Teepluss\Asset\AssetServiceProvider',
```

so that it'll look something like the following

```php
'providers' => array(

	...
	...
	...
	'Teepluss\Asset\AssetServiceProvider',

),
```

and add the following code to the `aliases` section of the `app/config/app.php` file

```php
'Asset' => 'Teepluss\Asset\Facades\Asset'
```

so that it'll look something like the following

```php
'aliases' => array(

	...
	...
	...
	'Asset'       => 'Teepluss\Asset\Facades\Asset',

),
```