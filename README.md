# A tool to allow BelongsTo searchable fields to be pre-populated with data

[![Latest Version on Packagist](https://img.shields.io/packagist/v/alexbowers/nova-prepopulate-searchable.svg?style=flat-square)](https://packagist.org/packages/alexbowers/nova-prepopulate-searchable)
[![Quality Score](https://img.shields.io/scrutinizer/g/alexbowers/nova-prepopulate-searchable.svg?style=flat-square)](https://scrutinizer-ci.com/g/alexbowers/nova-prepopulate-searchable)
[![Total Downloads](https://img.shields.io/packagist/dt/alexbowers/nova-prepopulate-searchable.svg?style=flat-square)](https://packagist.org/packages/alexbowers/nova-prepopulate-searchable)

## Note
This package is incompatible with [Create or add package](https://github.com/Abhi0725/nova-create-or-add). The Mainteners are no longer interested so i fixed both and will.

## Installation

You can install the package in to a Laravel app that uses [Nova](https://nova.laravel.com) via composer:

```bash
composer require mustafatoker/nova-prepopulate-searchable
```

## Usage

On any `BelongsTo` fields in your resources that are `searchable()`, you can also add `prepopulate()` to the method chain and the field will be prepopulated with values to choose from.

You may optionally pass through a search query to the prepopulate method, and the keywords passed will be used for
the search initially, before resetting the search to being empty (as it currently is).

![Prepopulate Search](https://github.com/alexbowers/nova-prepopulate-searchable/blob/master/screenshots/example.gif?raw=true)


## Credits

- [Alex Bowers](https://github.com/alexbowers)
- [Mustafa TOKER](https://github.com/mustafatoker)
- [Burak TEKİN](https://github.com/tekinburak)
- [Mustafa DEMİR](https://github.com/mstfdmr)
- [Salih KANDEMİR](#)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
