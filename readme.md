# example tenant website

Please note this repository is simply an example of the possibilities within one tenant website directory.

In order to make such a structure work you will need the [hyn multi tenancy](http://github.com/hyn-me/multi-tenant) 
package. This package is meant for [Laravel 5.1+](http://laravel.com).

The following structure is possible. Please note that all of these are optional!

You will find the directory stored by default under `/storage/multi-tenant/<websiteId>-<identifier>/`:

- [routes.php](https://github.com/hyn-me/dummy-tenant-website/blob/master/routes.php)
- [providers.php](https://github.com/hyn-me/dummy-tenant-website/blob/master/providers.php)
- [composer.json](https://github.com/hyn-me/dummy-tenant-website/blob/master/composer.json); set up whatever requirements and custom autoloading facilities. Please note you have to run `composer update` etc which creates the `vendor/autoload.php` file.
- /cache
- /config
- /lang
- [/media](https://github.com/hyn-me/dummy-tenant-website/blob/master/media/readme.md)
- /vendor
- /views