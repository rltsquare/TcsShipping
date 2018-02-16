# TcsShipping

# Overview

TCS Shipping Solution is a Magento 2 extension that allows the merchant to integrate with TCS Courier as their logistics partner by calculating delivery charges in a flexible manner.

Here are some of the salient features for the extension:

```
1. Seamless integration of your online store with TCS shipping API
2. User-friendly and easy to use backend panel for setting shipment variables (min. cart price, prices per kg according to the three payment methods)
3. You can offer free shipping if the customer reaches a specific order value
4. Compatibility with all payment methods.
5. Tracking of the shipment via email by the customer
```

## Installation

1. Go to Magento® 2 root folder

2. Require/Download this extension:

   Enter following commands to install extension.

   ```
   composer require rltsquare/tcs-shipping
   ```

   Wait while composer is updated.
 
3. Enter following commands to enable the module:

   ```
   php bin/magento module:enable RLTSquare_TcsShipping
   php bin/magento setup:upgrade
   php bin/magento cache:clean
   php bin/magento cache:flush
   ```

4. If Magento® is running in production mode, deploy static content and then clear the cache: 

   ```
   php bin/magento setup:static-content:deploy
   ```


## Requirements

This Magento® extension works on Magento 2.1 and 2.2 versions. Tested on versions 2.1.6 and above.

For details, read our blog:
https://www.rltsquare.com/blog/tcs-magento-2-extension/
