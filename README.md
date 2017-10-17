# users

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]


## Structure

If any of the following are applicable to your project, then the directory structure should follow industry best practises by being named the following.

```
bin/        
config/
src/
tests/
vendor/
```


## Install

Via Composer

``` bash
$ composer require pdavila13/users
```

## Usage

``` php
$users = new pdavila13\users();
echo $users->echoPhrase('Hello, League!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email info@paolodavila.com instead of using the issue tracker.

## Credits

- [Paolo Davila][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/pdavila13/users.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/pdavila13/users/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/pdavila13/users.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/pdavila13/users.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/pdavila13/users.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/pdavila13/users
[link-travis]: https://travis-ci.org/pdavila13/users
[link-scrutinizer]: https://scrutinizer-ci.com/g/pdavila13/users/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/pdavila13/users
[link-downloads]: https://packagist.org/packages/pdavila13/users
[link-author]: https://github.com/pdavila13
[link-contributors]: ../../contributors
