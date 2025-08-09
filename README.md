# My First Package

A small test package to learn how to create and publish a Composer package.

## Installation

You can install this package via Composer:

```bash
composer require mhdalik/my-first-package
```

## Usage

```php
<?php

require 'vendor/autoload.php';

use Mhdalik\MyFirstPackage\HelloWorld;

echo HelloWorld::sayHi();
```

Output:

```
Hello from my first package!
```

## License

This package is open-sourced software licensed under the [MIT license](LICENSE).
