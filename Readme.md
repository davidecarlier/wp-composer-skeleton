# WP Composer Skeleton

An easy way to install and manage a WordPress website with composer.

## Quickstart

You need to have PHP and [composer](https://getcomposer.org/) installed and available on the command line.

- Download or clone this repo
- Lanch `composer install`
- Copy wp-config-sample.php into wp-config.php and set it up.

Done!
Put your custom code into wp-content (as usual) and enjoy.

## Install plugins and themes with WordPress Packagist

To install plugin via composer you may use [wpackagist.org](https://wpackagist.org/).

Example:
`composer require "wpackagist-plugin/classic-editor":"1.6.2"`

Check .gitignore file to commit your custom or non-free plugins.
