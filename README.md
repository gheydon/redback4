# U2 Web Development Environment 4 (RedBack) for PHP
Provides communication with RocketSoftware’s RedBack 4.2+ server to allow access to the u2 database environments.

This is only a communication class which allows the [RedBack](https://github.com/gheydon/redback) to communicate with the RedBack scheduler (v4.2+) server.
## Installation
Installation via [composer](http://getcomposer.com) is the only method supported at this stage. Edit your composer.json to add the following.
``` js
{
    "require": {
        // ...
        "heydon/redback4": "1.0.x"
    }
}
```
##Usage
Using the uObject object you are able make a connection with the back end server.
``` php
$uObject->connect('RedBack4://127.0.0.1:8401');
````
