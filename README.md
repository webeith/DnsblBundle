DnslBundle
=====
[![License](https://poser.pugx.org/webeith/dnsbl/license.png)](https://packagist.org/packages/webeith/dnsbl)
[![Total Downloads](https://poser.pugx.org/webeith/dnsbl-bundle/downloads.png)](https://packagist.org/packages/webeith/dnsbl-bundle)

* [See how to use service](http://github.com/webeith/dnsbl)

Usage Example
-------------

``` php
$this->getContainer()->get('dnsbl');
```

## Installation

### Install via Composer

Add the following lines to your `composer.json` file and then run `php composer.phar install` or `php composer.phar update`:

```json
{
    "require": {
        "webeith/dnsbl-bundle": "dev-master"
    }
}
```

### Register the bundle

To start using the bundle, register it in `app/AppKernel.php`:

```php
public function registerBundles()
{
    $bundles = array(
        // Other bundles...
        new Webeith\DnsblBundle\WebeithDnsblBundle(),
    );
}
```
