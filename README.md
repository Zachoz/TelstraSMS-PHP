TelstraSMS-PHP
==============

A PHP wrapper for the Telstra SMS API.

##Usage::
```php
<?php
    $sms = new TelstraSMS($appKey, $appSecret, $recipient, $message); // Construct new SMS object
    $sms->send(); // Send the SMS

    $sms->getStatus(); // Gets the status of the message (json response)
    ?>
```
