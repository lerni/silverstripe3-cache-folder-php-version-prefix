# SilverStripe 3 Composer installable patch to add PHP-Version to path in silverstrpe-cache (prevent 503 on php version change)

- https://github.com/silverstripe/silverstripe-framework/issues/2986
- https://github.com/silverstripe/silverstripe-framework/pull/6810

## Requirements
* SilverStripe ~3.6 (just tested with that)

## Installation
Use [composer](https://getcomposer.org/):
`composer require lerni/silverstripe3-cachefolder-phpversion-prefix`