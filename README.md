# PHP Desktop


Table of contents:
* [Introduction](#introduction)
* [Downloads](#downloads)
* [Support](#support)
* [Donate](#donate)


## Introduction

PHP Desktop is an open source project founded by Czarek Tomczak in 2012 to provide a way for developing native 
desktop GUI applications using web technologies such as PHP, HTML5, JavaScript and SQLite. The development workflow 
you are used to while creating web applications remains the same. There is no new API/framework to learn. The process 
of turning an existing website into a desktop application is basically a matter of copying it to the "phpdesktop/www/" 
directory.

In a certain sense phpdesktop acts as a PHP to EXE compiler. It embeds a web browser, a multithreaded web server 
and a PHP interpreter. All embedded into a single application. The web server embedded is 
[Mongoose](https://en.wikipedia.org/wiki/Mongoose_(web_server)) (the MIT-licensed version). Supported browsers are
Internet Explorer and Google Chrome. The package with Chrome embedded has no external dependencies, everything 
is included in the phpdesktop binaries and works out of the box on a user's computer.

All popular PHP frameworks are supported, see the [PHP frameworks support](../../wiki/PHP-frameworks-support) wiki page 
for example configurations for CakePHP, CodeIgniter, Laravel, Symfony, Yii and Zend Framework.  You can create 
a standalone executable for distribution with the help of the 
[Inno Setup installer](../../wiki/Knowledge-Base#application-installer). PHP sources can be protected with the many
of the available [PHP encoders](../../wiki/Knowledge-Base#how-do-i-protect-php-sources-in-the-www-directory).
PHP Desktop is released under non-restrictive license, thus it is 
[free for commercial use](../../wiki/Knowledge-Base#can-i-use-php-desktop-in-a-commercial-closed-sourced-project).

It is one of the top goals for PHP Desktop to be stable, to work reliably. PHP Desktop does not suffer from memory leaks. 
PHP by design was never intended for running long hours/days, as desktop applications usually do. This is not a concern 
when using PHP Desktop, as it is running an internal web server and serving pages through CGI. So when PHP script ends 
execution PHP-CGI process is killed and all memory is always freed.

Lots of other useful information can be found on the [Knowledge Base](../../wiki/Knowledge-Base) wiki page and on the 
[PHP Desktop Forum](https://groups.google.com/d/forum/phpdesktop).


## Downloads

  * PHP Desktop Chrome - go to the [Download Chrome](../../wiki/Download-Chrome) wiki page.
  * PHP Desktop MSIE (Internet Explorer) - go to the [Download MSIE](../../wiki/Download-MSIE) wiki page.

__New releases RSS/Atom feed__  
To be notified of new releases subscribe to this [Atom feed](https://github.com/cztomczak/phpdesktop/releases.atom).


## Support

* Documentation is on the [Wiki Pages](../../wiki). Start with the [Knowledge Base](../../wiki/Knowledge-Base), 
    [Settings](../../wiki/Settings) and [Chrome settings](../../wiki/Chrome-settings) wiki pages.
* Ask questions and report problems on the [PHP Desktop Forum](https://groups.google.com/d/forum/phpdesktop)
* Please do not create issues in the Issue Tracker
* See also this tutorial (externally maintained): [Create your first Desktop Application with PHP and PHP Desktop](http://phpocean.com/tutorials/design-and-illustration/create-your-first-desktop-application-with-php-and-php-desktop/4)

