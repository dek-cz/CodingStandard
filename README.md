# CodingStandard

[![Downloads this Month](https://img.shields.io/packagist/dm/dek-cz/coding-standard.svg)](https://packagist.org/packages/dek-cz/coding-standard)
[![Latest stable](https://img.shields.io/packagist/v/dek-cz/coding-standard.svg)](https://packagist.org/packages/dek-cz/coding-standard)

DEK coding style rules of [PHPCodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer).

## Installation

Install the [`dek-cz/coding-standard`](https://packagist.org/packages/dek-cz/coding-standard) with [Composer](https://getcomposer.org):

```sh
composer require --dev dek-cz/coding-standard
```

## Usage

Just include the `ruleset.xml` standard in you project's `ruleset.xml`

```xml
<?xml version="1.0"?>
<ruleset name="My Project">
    <rule ref="vendor/dek-cz/coding-standard/DekCodingStandard/ruleset.xml"/>

    <!-- custom settings -->
</ruleset>
```
