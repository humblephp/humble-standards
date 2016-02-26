# humble-standards

[![Latest Version](https://img.shields.io/github/release/humblephp/humble-standards.svg)](https://github.com/humblephp/humble-standards/releases)
[![Software License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md)
[![Build Status](https://api.travis-ci.org/humblephp/humble-standards.svg?branch=master)](https://travis-ci.org/humblephp/humble-standards)

HUMBLE Standards

- PHPCS ruleset
- PHPMD ruleset

## Install

Via Composer

``` bash
$ composer require humble/standards
```

## Usage

Run PHPCS
```
./vendor/bin/phpcs ./src --extensions=php --standard=./vendor/humble/standards/ruleset/phpcs.xml
```

Run PHPMD
```
./vendor/bin/phpmd ./src text ./vendor/humble/standards/ruleset/phpmd.xml
```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
