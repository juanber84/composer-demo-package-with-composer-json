# Composer demo package with composer.json

## How load the library

```
{
    "repositories": [
        {
            "url": "https://github.com/juanber84/composer-demo-package-with-composer-json.git",
            "type": "git"
        }
    ],
    "require": {
        "demo/composer-good": "dev-master"

    }
}
```

## Usage

```php
<?php

require 'vendor/autoload.php';

use Demo\Hello;

$object = new Hello();
$object->setName('Juan');
$object->greet();
```
