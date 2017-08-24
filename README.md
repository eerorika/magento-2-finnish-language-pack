## Magento 2 Finnish Language Pack

**Magento 2 Finnish Language Pack** is the perfect guide so that you can enable Finnish on your magento 2 store. This translation is really necessary for everyone who are living in the Finland. Here is a step-by-step guide to install Finnish package and use it as the default language.

Read more [Magento 2 Finnish Language Pack](https://www.mageplaza.com/magento-2-finnish-language-pack.html)


## Overview

- Download & Contribute
- Install Finnish Language Pack
- How to Install Finnish Language Pack

## Download & Contribute to Finnish Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Finnish Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-finnish-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-finnish-language-pack/tarball/master)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Finnish Language Pack

There are 3 different methods to install this language pack.

### ✓ #1. Composer method (Recommend)
Install the Finnish language pack via composer is never easier.

**Install Finnish pack**:

```
composer require mageplaza/magento-2-finnish-language-pack:dev-master
php bin/magento setup:static-content:deploy fi_FI
php bin/magento cache:clean
php bin/magento cache:flush

```


**Update  Finnish pack**:

```
composer update mageplaza/magento-2-finnish-language-pack:dev-master
php bin/magento setup:static-content:deploy fi_FI
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

#### Authentication required (Optional)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### #2. Copy & Paste method (Not recommend)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Finnish language pack
- Step 2: Unzip Finnish pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Finnish language pack

You can download the language pack from above link

#### Step 2: Unzip Finnish pack

Unzip the Finnish language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually (Not recommend)

To download and install Finnish pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-finnish-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-finnish-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `fi_FI.zip` into `app/i18n/mageplaza/fi_FI/fi_FI.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active Finnish language pack

Now time to active the Finnish language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Finnish language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


<!-- ## Translation process of Finnish Language Pack
![process](http://progressed.io/bar/80) -->

Contribute to this language at https://crowdin.com/project/magento-2/fi

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.0.9
- Magento v2.0.10
- Magento v2.0.11
- Magento v2.0.12
- Magento v2.0.13
- Magento v2.0.14
- Magento v2.0.15
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2
- Magento v2.1.3
- Magento v2.1.4
- Magento v2.1.5
- Magento v2.1.6
- Magento v2.1.7
- Magento v2.1.8



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## References:

- https://www.mageplaza.com/magento-2-finnish-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/
- https://crowdin.com/project/magento-2



## SWEET MAGEPLAZA EXTENSIONS TO BRING YOU MORE MONEY

### [✓ One Step Checkout](https://www.mageplaza.com/magento-2-one-step-checkout-extension/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ ↑30% INCREASE CONVERSION RATE 

☞ ↓66% DECREASE ABANDONMENT CART

☞ ↓80% REDUCE CHECKOUT TIME

### [✓ Layered Navigation](https://www.mageplaza.com/magento-2-layered-navigation-extension/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ ↑84% USER'S FILTERING EXPERIENCE

☞ ↑25% CONVERSION RATE

☞ ↓67% SHOPPING TIME

### [✓ Frequently Bought Together](https://www.mageplaza.com/magento-2-frequently-bought-together/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Amazon Product Recommendation Solution
 
☞ AJAX loading for better performance

☞ Support Custom Options and all product types



### [✓ Gift Card](https://www.mageplaza.com/magento-2-gift-card-extension/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Physical, virtual or combined gift cards
 
☞ Different gift card values from prices

☞ Send cards via email, SMS, post office or messenger


### [✓ Who Bought This Also Bought](https://www.mageplaza.com/magento-2-who-bought-this-also-bought/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Display on Product Page, Category Page, Shopping Cart page

☞ AJAX loading for better performance.

☞ Flexible layout and design.


### [✓ Social Login](https://www.mageplaza.com/magento-2-social-login-extension/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Increase signup rate up-to 30%

☞ Supports 11 Types: Facebook, Google Plus, Twitter, Linkedin, Instagram, Yahoo, Github, Foursquare, VK, Live, Amazon

☞ Easy custom design fit with your store design

☞ [Social Login on Github](https://github.com/mageplaza/magento-2-social-login)



### [✓ Shop By Brand](https://www.mageplaza.com/magento-2-shop-by-brand/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Fully Compatible with Layered Navigation

☞ Instant Search brands

☞ Import brands




### [✓ Affiliate](https://www.mageplaza.com/magento-2-affiliate-extension/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Multiple Affiliate Campaigns

☞ Smart Referral Links

☞ Affiliate Report





## Mageplaza extensions on Magento Marketplace, Github


☞ [Magento 2 One Step Checkout extension](https://marketplace.magento.com/mageplaza-magento-2-one-step-checkout-extension.html)

☞ [Magento 2 Blog extension](https://marketplace.magento.com/mageplaza-magento-2-blog-extension.html)

☞ [Magento 2 Layered Navigation extension](https://marketplace.magento.com/mageplaza-layered-navigation-m2.html)

☞ [Magento One Step Checkout](https://github.com/magento-2/one-step-checkout)

☞ [Magento 2 Blog on Github](https://github.com/mageplaza/magento-2-blog)

☞ [Magento 2 Social Login on Github](https://github.com/mageplaza/magento-2-social-login)

☞ [Magento 2 SEO on Github](https://github.com/mageplaza/magento-2-seo)

☞ [Magento 2 SMTP on Github](https://github.com/mageplaza/magento-2-smtp)

☞ [Magento 2 Product Slider on Github](https://github.com/mageplaza/magento-2-product-slider)

☞ [Magento 2 Banner on Github](https://github.com/mageplaza/magento-2-banner-slider)



