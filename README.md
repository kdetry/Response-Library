# Response-Library
Response Library for PHP Applications. 
Ideal for modular mvc applications

# Usage

```php
<?php
$item = array(
'title' => 'Foo Bar'
);


$response = new Response();
$response->setOutput($response->view('fooView.php', $item));
$response->output();
```

In view / fooView.php

```php
<?php echo $title; ?>
```