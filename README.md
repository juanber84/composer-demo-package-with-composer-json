# Composer demo package with composer.json

## Usage

```php
<?php

require 'vendor/autoload.php';

use Demo\Hello;

$object = new Hello();
$object->setName('Juan');
$object->greet();
```
