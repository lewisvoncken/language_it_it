# Italian (italiano) Magento2 Language Pack (it_IT)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Italian (italiano) translations used can be found [here](https://crowdin.com/project/magento-2/it).
This translation is usefull for people living in the Italy (Italia).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [Head](https://crowdin.com/project/magento-2/it#/Head) at Crowdin and based on the Magento 2.1.4 sourcefiles.
There have been  7622 strings translated of the 8458 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/90)

# Instalation
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_it_it:dev-master
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_it_it/archive/master.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_it_it`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/it_IT/it_IT.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Italian (Italy)*'

# Contribute
To help push the '*Italian (italiano) Magento2 Language Pack (it_IT)*' forward please goto [this](https://crowdin.com/project/magento-2/it) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).