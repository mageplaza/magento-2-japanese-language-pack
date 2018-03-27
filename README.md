## Magento 2 Japanese Language Pack

**Magento 2 Japanese Language Pack** is totally free translation guide for every eCommerce stores. The language package is a critical documentation if you want to translate from English to Japanese. As you can see, although English has been becoming the most popular language in the world, presenting native language in each country is still a must. Not only does this create good impression from the audience but you will not have any difficulty in the exchange.

Read more [Magento 2 Japanese Language Pack](https://www.mageplaza.com/magento-2-japanese-language-pack.html)


## Overview

- Download & Contribute
- Install Japanese Language Pack
- How to Install Japanese Language Pack

## 1. Download & Contribute to Japanese Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Japanese Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-japanese-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-japanese-language-pack/tarball/master)


Find other [language packs here](https://www.mageplaza.com/kb/magento-2-language-pack/)

## 2. How to Install Japanese Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Japanese language pack via composer is never easier.

**Install Japanese pack**:

```
composer require mageplaza/magento-2-japanese-language-pack:dev-master
php bin/magento setup:static-content:deploy ja_JP
php bin/magento cache:flush

```


**Update  Japanese pack**:

```
composer update mageplaza/magento-2-japanese-language-pack:dev-master
php bin/magento setup:static-content:deploy ja_JP
php bin/magento cache:flush

```

#### Authentication required (If any)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Japanese language pack
- Step 2: Unzip Japanese pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Japanese language pack

You can download the language pack from above link

#### Step 2: Unzip Japanese pack

Unzip the Japanese language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip app/code/Mageplaza/ja_jp
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### ✓ Method #3. Download and install manually (Not recommended)

To download and install Japanese pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-japanese-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-japanese-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `ja_JP.zip` into `app/i18n/mageplaza/ja_JP/ja_JP.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## 3. How to active Japanese language pack

Now time to active the Japanese language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Japanese language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


## 4. How to contribute
<!-- ![process](http://progressed.io/bar/80) -->

Contribute to this language at https://crowdin.com/project/magento-2/ja

## Supported Magento versions

- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x



## Note

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue](https://github.com/mageplaza/magento-2-japanese-language-pack/issues/new)

## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## References:

- https://www.mageplaza.com/magento-2-japanese-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/
- https://crowdin.com/project/magento-2








## Mageplaza extensions on Magento Marketplace, Github



☞ [Blog](https://github.com/mageplaza/magento-2-blog)

☞ [Social Login](https://github.com/mageplaza/magento-2-social-login)

☞ [SEO](https://github.com/mageplaza/magento-2-seo)

☞ [SMTP](https://github.com/mageplaza/magento-2-smtp)

☞ [Product Sliderthub](https://github.com/mageplaza/magento-2-product-slider)

☞ [Banner](https://github.com/mageplaza/magento-2-banner-slider)

☞ [Sample Payment Method](https://github.com/mageplaza/magento-2-sample-payment-method)



