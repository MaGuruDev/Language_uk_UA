# MaGuru Language Pack uk_UA for Magento 2

![Magento 2](https://img.shields.io/badge/Magento-2.4%2B-brightgreen)
[![Stable Version](https://poser.pugx.org/maguru/magento2-language-uk-ua/v/stable)](https://packagist.org/packages/maguru/magento2-language-uk-ua)
[![Total Downloads](https://poser.pugx.org/maguru/magento2-language-uk-ua/downloads)](https://packagist.org/packages/maguru/magento2-language-uk-ua)

<img width="150" height="100" src="documentation/images/made_in_ukraine.jpeg">

---

> Ukrainian translation for Magento 2. Translation uk_UA (Ukrainian (Ukraine)).

## Supported Magento versions

- ✅ Magento 2.4.0 - 2.4.7+
- ✅ Magento 2.3.x (limited support)

## How to install & upgrade MaGuru_uk_UA

### 1. Install via composer (recommend)

* We recommend you to install MaGuru_uk_UA module via composer. It is easy to install, update and maintaince.

* Run the following command in Magento 2 root folder.

#### 1.1 Install

```
composer require maguru/magento2-language-uk-ua:1.0.7
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

#### 1.2 Upgrade

```
composer update maguru/magento2-language-uk-ua:1.0.7
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run compile if your store in Product mode:

```
php bin/magento setup:di:compile
```

