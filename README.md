# A very basic Composer package

## Installation

### With Composer

```
$ composer require stephanpaquet/hello_world
```

```json
{
    "require": {
        "stephanpaquet/hello_world": "^1.0"
    }
}
```

```php
<?php
# test.php
require 'vendor/autoload.php';

use HelloWorld\SayHello;

echo SayHello::world();

# output 
Hello World, Composer

```

## Inspiration
http://blog.grossi.io/2013/creating-your-first-composer-packagist-package/

## Todo

- [ ] add some test
