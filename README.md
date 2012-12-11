ZF2 Singly Module Example Application
=====================================

Introduction
------------
This is a simple module to show your weight over time as a graph from Fitbit using the Singly API.


Installation
------------
Run these commands 

```
git clone git@github.com:TomHAnderson/Singly
cd Singly
git checkout example
./composer.phar install
```

Edit config/autoload/module.singly.local.php and add your Singly credentials

```
return array(
    'singly' => array(
        'client_id' => "abcdefgh",
        'client_secret' => "12345678",
```

Fire up PHP 5.4 from the public directory with 

```
php -S localhost:8080
```

and browse to 

```
http://localhost:8080
```