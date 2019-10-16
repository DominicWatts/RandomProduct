# Magento 2 Random Products Offers Page #

Frontend controller to display all products with with layered navigation. Plus widget which pulls through random product(s) from whole of catalog. Any additional rules that would apply to a product collection on your store such as visibility or stock.

# Install instructions #

`composer require dominicwatts/randomproduct`

`php bin/magento setup:upgrade`

`php bin/magento setup:di:compile`

# Usage instructions #

Go to `/all-products` or use header link

## Widget

There is a widget for use in layout, blocks and CMS pages which is configurable via backend.
