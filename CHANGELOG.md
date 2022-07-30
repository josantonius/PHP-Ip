# CHANGELOG

## 1.1.8 - 2022-07-30

The repository was archived.

>After reviewing the code after a few years, I would not recommend the use of the class for a
>production site, as preference was given to headers easily manipulated by the user to get the IP.

>If the reliability of the header from which the IP will be obtained is not guaranteed,
>it is better to use $_SERVER['REMOTE_ADDR'] directly or develop a custom solution.

## 1.1.7 - 2018-01-06

* The tests were fixed.

* Changes in documentation.

## 1.1.6 - 2017-11-08

* Implemented `PHP Mess Detector` to detect inconsistencies in code styles.

* Implemented `PHP Code Beautifier and Fixer` to fixing errors automatically.

* Implemented `PHP Coding Standards Fixer` to organize PHP code automatically according to PSR standards.

## 1.1.5 - 2017-11-01

* Implemented `PSR-4 autoloader standard` from all library files.

* Implemented `PSR-2 coding standard` from all library PHP files.

* Implemented `PHPCS` to ensure that PHP code complies with `PSR2` code standards.

* Implemented `Codacy` to automates code reviews and monitors code quality over time.

* Implemented `Codecov` to coverage reports.

* Added `Ip/phpcs.ruleset.xml` file.

* Deleted `Ip/src/bootstrap.php` file.

* Deleted `Ip/tests/bootstrap.php` file.

* Deleted `Ip/vendor` folder.

* Changed `Josantonius\Ip\Test\IpTest` class to  `Josantonius\Ip\IpTest` class.

* Added `Josantonius\Ip\Ip::getGlobalValue()` method.

## 1.1.4 - 2017-09-14

* Unit tests supported by `PHPUnit` were added.

* The repository was synchronized with Travis CI to implement continuous integration.

* Added `Ip/src/bootstrap.php` file

* Added `Ip/tests/bootstrap.php` file.

* Added `Ip/phpunit.xml.dist` file.
* Added `Ip/_config.yml` file.
* Added `Ip/.travis.yml` file.

* Deleted `Josantonius\Ip\Tests\IpTest::testGetIp()` method.

* Added `Josantonius\Ip\Test\IpTest::testValidateIp()` method.
* Added `Josantonius\Ip\Test\IpTest::testValidateWrongIp()` method.
* Added `Josantonius\Ip\Test\IpTest::testGetIp()` method.

## 1.1.3 - 2017-07-16

* Deleted `Josantonius\Ip\Exception\IpException` class.
* Deleted `Josantonius\Ip\Exception\Exceptions` abstract class.
* Deleted `Josantonius\Ip\Exception\IpException->__construct()` method.

## 1.1.2 - 2017-07-09

* Added `Josantonius\Ip\Ip::validate()` method.

## 1.1.1 - 2017-03-18

* Some files were excluded from download and comments and readme files were updated.

## 1.1.0 - 2017-01-30

* Compatible with PHP 5.6 or higher.

## 1.0.0 - 2017-01-30

* Compatible only with PHP 7.0 or higher. In the next versions, the library will be modified to make it compatible with PHP 5.6 or higher.

## 1.0.0 - 2017-01-17

* Added `Josantonius\Ip\Ip` class.
* Added `Josantonius\Ip\Ip::get()` method.

## 1.0.0 - 2017-01-17

* Added `Josantonius\Ip\Exception\IpException` class.
* Added `Josantonius\Ip\Exception\Exceptions` abstract class.
* Added `Josantonius\Ip\Exception\IpException->__construct()` method.

## 1.0.0 - 2017-01-17

* Added `Josantonius\Ip\Tests\IpTest` class.
* Added `Josantonius\Ip\Tests\IpTest::testGetIp()` method.
