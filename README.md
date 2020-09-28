# Module Hello Admin


## Installation Guide

### Type 1: Zip file

 - Unzip the theme zip file in `app/code/CsVikram/HelloAdmin`
 - Apply database updates by running `php bin/magento setup:upgrade`
 - Disable module by running `php bin/magento module:disable CsVikram_HelloAdmin`
 - Enable module by running `php bin/magento module:enable CsVikram_HelloAdmin`
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Install the luma child theme by running `composer require csvikram/helloadmin:dev-master`
 - apply database updates by running `php bin/magento setup:upgrade`
 - Flush the cache by running `php bin/magento cache:flush`
