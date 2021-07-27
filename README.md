# AlphaID

## Install

```bash
composer require sy-records/alphaid
```

## Usage

```php
use Luffy\AlphaID;

$id = new AlphaID();
$code = $id->encode(PHP_INT_MAX);
var_dump($code, $id->decode($code));
```
