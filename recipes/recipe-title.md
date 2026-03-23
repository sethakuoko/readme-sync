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

$response = $client->request('POST', 'https://uxcam.sethakuoko.online/api/v1/crashes');

echo $response->getBody();
```

```json Response Example
{"success":true}
```

# Step 1

<!-- php@1 -->

Step description

# Step 2

<!-- php@2-5 -->

Step 2 description

# Step 3

<!-- php@ -->

step 3 desc