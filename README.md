slim-minify
===========

Slim middleware to minify HTML output generated by the slim PHP framework. It removes whitespaces, empty lines and tabs 
beetween html-tags to reduce traffic. This script is a summary of stackoverflow answers.

## Usage

Copy the file Minify.php to 'Slim/Extras/Middleware/'. Register minify via $app->add():

```php
$app = new \Slim\Slim(.....));
$app->add(new \Slim\Extras\Middleware\Minify() );
```

## Contributors

* Christian Klisch http://www.christian-klisch.de


## Copyright and license

Copyright 2014 released under [MIT](LICENSE) license.