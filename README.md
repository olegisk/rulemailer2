#Rulemailer2#
Magento 2 integration module for the [Rule](https://www.rule.se/).

#Installation#

##Install via composer##
In the terminal `cd` to the root of your magento project. Then run:
```bash
composer require rulecom/rulemailer2
php bin/magento setup:upgrade
php bin/magento setup:di:compile

#Configuration#
In the admin part of your Magento app select `Stores/Configuration` section. Then select `RULE/Rulemailer` from the left menu.
In the form enter your Api key from the RULE appliction. If 'Use transactional' field set to 'Yes' all mail from the your Magento app are going to be sent via RULE transactional api.