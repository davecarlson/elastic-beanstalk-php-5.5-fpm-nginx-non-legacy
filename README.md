

This is the sample config of .ebextensions to setup an Elastic Beanstalk PHP 5.5 container using Nginx and PHP-FPM.


Using the non-legacy containers allows you to use Nginx (or any other services that you would like to) without the need of building a customised AMI.

Tested on ami-4b18e33c, PHP 5.5 default. Could work with others.


Many thanks to https://github.com/duyoji/elastic-beanstalk-php-5.4-fpm-nginx-non-legacy for the base.





