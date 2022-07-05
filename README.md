# Magento 2 All Products Landing Page and Random Products Widget #

[![M2 Coding Standard](https://github.com/DominicWatts/RandomProduct/actions/workflows/phpcs.yml/badge.svg)](https://github.com/DominicWatts/RandomProduct/actions/workflows/phpcs.yml)

[![M2 PHPStan](https://github.com/DominicWatts/RandomProduct/actions/workflows/phpstan.yml/badge.svg)](https://github.com/DominicWatts/RandomProduct/actions/workflows/phpstan.yml)

[![PHP Compatibility](https://github.com/DominicWatts/RandomProduct/actions/workflows/phpcompatibility.yml/badge.svg)](https://github.com/DominicWatts/RandomProduct/actions/workflows/phpcompatibility.yml)

[![php-cs-fixer](https://github.com/DominicWatts/RandomProduct/actions/workflows/phpcsfixer.yml/badge.svg)](https://github.com/DominicWatts/RandomProduct/actions/workflows/phpcsfixer.yml)

Frontend controller to display all products with with layered navigation. Plus widget which pulls through random product(s) from whole of catalog. Any additional rules that would apply to a product collection on your store such as visibility or stock.

# Install instructions #

`composer require dominicwatts/randomproduct`

`php bin/magento setup:upgrade`

`php bin/magento setup:di:compile`

# Usage instructions #

Go to `/all-products` or use header link

## Widget

There is a widget for use in layout, blocks and CMS pages which is configurable via backend.
