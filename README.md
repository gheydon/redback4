# U2 Web Development Environment 4 (RedBack) for PHP
Provides communication with RocketSoftware’s RedBack 4.2+ server to allow access to the u2 database environments.

This is only a communication class which allows the [RedBack](https://github.com/gheydon/redback) to communicate with the RedBack scheduler (v4.2+) server.

##Usage
Using the uObject object you are able make a connection with the back end server.   
`$uObject->connect(‘RedBack4://127.0.0.1:8401’);`   
