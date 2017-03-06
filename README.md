# ZipCode Validator
[![Latest Stable Version](https://poser.pugx.org/uvinum/zipcodevalidator/v/stable)](https://packagist.org/packages/uvinum/zipcodevalidator)
[![License](https://poser.pugx.org/uvinum/zipcodevalidator/license)](https://packagist.org/packages/uvinum/zipcodevalidator)
[![Build Status](https://travis-ci.org/uvinum/zipcode-validator.svg?branch=master)](https://travis-ci.org/uvinum/zipcode-validator)


A PHP library that provides zip code validation for many countries.

## Prerequisites

PHP >= 7.0


## Install

Via Composer

``` bash
$ composer require uvinum/zipcode-validator
```

## Usage

```
<?php
$zip_code_validator = new Validator();
$zip_code_validator->validate($a_country_iso_code, $a_zip_code);
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Acknowledgments

* Based on [https://github.com/barbieswimcrew/zip-code-validator](https://github.com/barbieswimcrew/zip-code-validator/ "barbieswimcrew/zip-code-validator") Symfony Constraint class

## Security

If you discover any security related issues, please email developers at uvinum.com instead of using the issue tracker.

## Credits

- [Uvinum](https://github.com/uvinum/)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
