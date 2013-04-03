Just port Laravel 3 Asset to Laravel 4.0.x

```php
'providers' => array(
	....
	'Teepluss\Asset\AssetServiceProvider'
);

'aliases' => array(
	....
	'Asset' 		  => 'Teepluss\Asset\Facades\Asset'
);
```