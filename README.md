# Magento 2 BuyNow 

This module add "BuyNow" button on product view page and list page to process directly checkout.

BuyNow Configuration: Stores->Configuration->MagePrince->Buy Now

# Notice

<b>We don't support Buy Now button on related, upsell, wishlist or any other places because it needs override core phtml files which is not the recommended solution. Please keep in note that most of the paid or free version of the Buy Now module overrides the core phtml files.</b>

# Installation Instruction

* Copy the content of the repo to the <b>app/code/Mageprince/BuyNow</b> folder
* Run command:
<b>php bin/magento setup:upgrade</b>
* Run Command:
<b>php bin/magento setup:static-content:deploy</b>
* Now Flush Cache: <b>php bin/magento cache:flush</b>

# Contribution

Want to contribute to this extension? The quickest way is to <a href="https://help.github.com/articles/about-pull-requests/">open a pull request</a> on GitHub.

# Support

If you encounter any problems or bugs, please <a href="https://github.com/mageprince/magento2-buynow/issues">open an issue</a> on GitHub.

<b>PRODUCT VIEW PAGE</b>

<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/BuyNow/listpage.png" alt="View Page" border="0">

<b>PRODUCT LIST PAGE</b>

<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/BuyNow/viewpage.png" alt="list page" border="0" />

# How To Find Addtocart Form Id - Useful For Custom Theme

Go to product view page and right click on addtocart button and click on inspect element. Then scroll up and find addtocart form id.

<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/BuyNow/formid.png" alt="Form ID" border="0" />
