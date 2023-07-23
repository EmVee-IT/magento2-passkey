# EmVeeIT Passkey Admin Magento 2 Module

This Magento 2 module replaces admin passwords with passkeys for an additional layer of security. It adds a console command that allows you to generate passkeys.

## Installation

Add the module to your project using composer:

```shell
composer require emveeit/passkey-admin
```
Enable the module in Magento:
```shell
bin/magento module:enable EmVeeIT_PasskeyAdmin
```
And then run setup upgrade:
```shell
bin/magento setup:upgrade
```

## Usage
You can generate passkeys by running the following console command:
```shell
bin/magento emveeit:generate:passkey
```

This will generate a new passkey, which you can use instead of a password when logging into the Magento admin.

## Unit Tests
To run the unit tests, first make sure that PHPUnit is installed. Then run the following command:
```shell
./vendor/bin/phpunit -c tests/phpunit.xml.dist
```
## Author
Michael Voeten @ EmVee IT

- Email: info@emvee-it.nl
- Website: https://www.emvee-it.nl/

## License
This project is licensed under the OSL-3.0 License - see the LICENSE file for details
```shell
Please replace `https://www.emvee-it.nl/` with your actual website link. If you don't have a `LICENSE` file, you might want to add one, or remove the reference to it in the readme. Adjust the installation and usage instructions as needed.
```
