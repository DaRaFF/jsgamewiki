---
layout: docs
title: Installation
prev_section: home
next_section: usage
permalink: /docs/installation/

---

wow, this is great

```php
<?php

use Monolog\Logger;
use Monolog\Handler\StreamHandler;

// create a log channel
$log = new Logger('name');
$log->pushHandler(new StreamHandler('path/to/your.log', Logger::WARNING));

// add records to the log
$log->addWarning('Foo');
$log->addError('Bar');
```
