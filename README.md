# omnisms-common
Common code used by OmniSMS gateway


# Omnisms

Omnisms is a SMS sending library for PHP. It has been designed based on
ideas from [Omnipay](https://github.com/thephpleague/omnipay). It has a clear and consistent API,
is fully unit tested, and even comes with an example application to get you started.

## Installation

Omnisms is installed via [Composer](http://getcomposer.org/). To install all officially
supported gateways, simply add the following to your `composer.json` file:

```json
{
    "require": {
        "omnisms/omnisms": "~2.0"
    }
}
```

Alternatively, you can require individual gateways:

```json
{
    "require": {
        "omnisms/paypal": "~2.0"
    }
}
```

Next, run composer to update your dependencies:

    $ curl -s http://getcomposer.org/installer | php
    $ php composer.phar update
