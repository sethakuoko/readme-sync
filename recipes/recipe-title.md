---
title: Recipe Title
description: Recipe Description
hidden: false
recipe:
  color: '#018FF4'
  icon: 🦉
---
```php PHP
<?php
require_once('vendor/autoload.php');

$client = new \GuzzleHttp\Client();

$response = $client->request('GET', 'https://uxcam.sethakuoko.online/api/v1/crashes/id');

echo $response->getBody();
```

```json Response Example
{"success":true}
```

# Step 1

<!-- php@ -->

Step description

# Step 2

<!-- php@ -->

Step 2 description