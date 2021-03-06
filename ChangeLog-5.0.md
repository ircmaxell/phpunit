# Changes in PHPUnit 5.0

All notable changes of the PHPUnit 5.0 release series are documented in this file using the [Keep a CHANGELOG](http://keepachangelog.com/) principles.

## [5.0.0] - 2015-10-02

### Added

* Merged [#1753](https://github.com/sebastianbergmann/phpunit/issues/1753): Added the `assertFinite()`, `assertInfinite()` and `assertNan()` assertions
* Implemented [#1656](https://github.com/sebastianbergmann/phpunit/issues/1656): Allow sorting test failures in reverse
* Implemented [#1780](https://github.com/sebastianbergmann/phpunit/issues/1780): Support for deep-cloning of results passed between tests using `@depends`

### Changed

* Merged [#1781](https://github.com/sebastianbergmann/phpunit/issues/1781): Empty string is not treated as a valid JSON string anymore

### Removed

* The `assertSelectCount()`, `assertSelectRegExp()`, `assertSelectEquals()`, `assertTag()`, `assertNotTag()` assertions have been removed
* The PHPUnit_Selenium component is no longer bundled in the PHAR distribution
* The PHPUnit_Selenium component can no longer be configured using the `<selenium/browser>` element of PHPUnit's configuration file
* PHPUnit is no longer supported on PHP 5.3, PHP 5.4, and PHP 5.5

[5.0.0]: https://github.com/sebastianbergmann/phpunit/compare/4.8...5.0.0

