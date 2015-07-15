# NameFromMyBundle

Build status: [![Build Status](https://travis-ci.org/PHPMailer/PHPMailer.svg)](https://travis-ci.org/PHPMailer/PHPMailer)
[![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/PHPMailer/PHPMailer/badges/quality-score.png?s=3758e21d279becdf847a557a56a3ed16dfec9d5d)](https://scrutinizer-ci.com/g/PHPMailer/PHPMailer/)
[![Code Coverage](https://scrutinizer-ci.com/g/PHPMailer/PHPMailer/badges/coverage.png?s=3fe6ca5fe8cd2cdf96285756e42932f7ca256962)](https://scrutinizer-ci.com/g/PHPMailer/PHPMailer/)

## About

The NameFromMyBundle provides Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
Phasellus tristique turpis vel magna condimentum cursus. Fusce finibus vestibulum quam 
eu iaculis. 

## Installation

Require the `vendor/my-bundle` package in your composer.json and update your dependencies.

```sh
$ composer require vendor/my-bundle
```

Add the NameFromMyBundle to your AppKernel.php

```php
public function registerBundles()
{
    $bundles = array(
        ...
        new Vendor\NameFromMyBundle\NameFromMyBundle(),
        ...
    );
    ...
}
```

## Usage

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus tristique turpis 
vel magna condimentum cursus. Fusce finibus vestibulum quam eu iaculis. Pellentesque 
varius, est non mattis condimentum, lectus sapien dictum metus, a venenatis metus 
sem ac arcu. Etiam tortor nisl, luctus vel dui in, fermentum facilisis elit. Aliquam 
pellentesque quam eget est molestie tempus. Maecenas semper mollis ante vitae pulvinar.

```php
$myVar = 25;
$anotherVar = 45;
$sum = $myVar + $anotherVar;

if ($sum > 70) {
    die('Ops! Sum incorrect!');
}
```

## License

Released under the XXXXX License, see LICENSE.
