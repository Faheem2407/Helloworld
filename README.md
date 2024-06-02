This is Just a basic "hello world package" created by me using composer you can use it inside your laravel project to see the output.

what's inside ?
---------------
There is just a Class SayHi.php

How to use it ?
---------------
Just create a fresh laravel project : composer create-project laravel/laravel YourProjectName
---------
Then go YourProject folder : cd YourProjectName
---------
To use my package: composer require faheem2407/helloworld
---------
Then :
------
     1.create a route
     2.use Faheem2407\Helloworld\SayHi;
     3.inside your closure just make an instance of this class pass yourName as a parameter : new SayHi("yourName");

It will show you the output like the following :

Output:
------
Hi yourName welcome to our testing helloworld package

