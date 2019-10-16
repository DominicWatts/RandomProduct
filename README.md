# Magento 2 Random Products Offers Page #

Frontend controller to display products with random offers with layered navigation.

For products to display they must be on random offer and with the random from and to date range.  Plus any additional rules that would apply to a product collection on your store such as visibility or stock.

![Screenshot](https://i.snag.gy/3GZ6wr.jpg)

# Install instructions #

`composer require dominicwatts/random`

`php bin/magento setup:upgrade`

`php bin/magento setup:di:compile`

# Usage instructions #

Go to `/random-offers` or use header link

## Widget

There is a widget for use in layout, blocks and CMS pages