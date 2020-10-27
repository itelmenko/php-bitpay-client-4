itelmenko/php-bitpay-client
=================


This is a self-contained PHP implementation of BitPay's new cryptographically secure API: https://bitpay.com/api

It's fork of [bitpay/php-bitpay-client](https://github.com/bitpay/php-bitpay-client) with support for Symfony v5.

# Installation

## Composer

### Install Composer

```bash
curl -sS https://getcomposer.org/installer | php
```

### Install via composer by hand

Add to your composer.json file by hand.

```javascript
{
    ...
    "require": {
        ...
        "bitpay/php-client": "^5.0"
    }
    ...
}
```

Once you have added this, just run:

```bash
php composer.phar update bitpay/php-client
```

### Install using composer

```bash
php composer.phar require bitpay/php-client:^5.0
```

## Documentation

Please see the ``docs`` directory for information on how to use this library
and the ``examples`` directory for examples on using this library. You should
be able to run all the examples by running ``php examples/File.php``.

The ``examples/tutorial`` directory provides four scripts that guide you with creating a BitPay invoice:
https://github.com/bitpay/php-bitpay-client/blob/master/examples/tutorial/

# Support

* https://github.com/bitpay/php-bitpay-client/issues
* https://support.bitpay.com

When you receive blank IPN responses, please check https://support.bitpay.com/hc/en-us/articles/115003025706-Why-am-I-getting-a-blank-IPN-post-response-from-BitPay-when-using-PHP-

# License

The MIT License (MIT)

Copyright (c) 2018 BitPay, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
