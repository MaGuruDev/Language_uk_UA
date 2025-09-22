# MaGuru MaGuru_uk_UA for Magento 2

![Magento 2](https://img.shields.io/badge/Magento-2.4%2B-brightgreen)

<img width="150" height="100" src="documentation/images/made_in_ukraine.jpeg">

---

> Ukrainian translation for Magento 2. Translation uk_UA (Ukrainian (Ukraine)).

## Requirements

* Magento Community Edition 2.1.x-2.4.x or Magento Enterprise Edition 2.1.x-2.4.x

## How to install & upgrade MaGuru_uk_UA

### 1. Install via composer (recommend)

* We recommend you to install MaGuru_uk_UA module via composer. It is easy to install, update and maintaince.

* Run the following command in Magento 2 root folder.

#### 1.1 Install

```
composer require maguru/magento2-uk_UA
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

#### 1.2 Upgrade

```
composer update maguru/magento2-uk_UA
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run compile if your store in Product mode:

```
php bin/magento setup:di:compile
```

