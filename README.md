# A very basic Composer package

## Installation

### With Composer

```
$ composer require stephanpaquet/hello_world
```

```json
{
    "require": {
        "stephanpaquet/hello_world": "~1.0.0"
    }
}
```

```php
<?php
require 'vendor/autoload.php';

use HelloWorld\SayHello;

echo SayHello::world();
```


- [ ] add some test
