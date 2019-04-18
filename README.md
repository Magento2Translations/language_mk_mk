# Macedonian (македонски) Magento2 Language Pack (mk_MK)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Macedonian (македонски) translations used can be found [here](https://crowdin.com/project/magento-2/mk).
This translation is usefull for people living in the North Macedonia (Северна Македонија).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [2.2.4](https://crowdin.com/project/magento-2/mk#/2.2.4) at Crowdin and based on the Magento 2.2.4 sourcefiles.
There have been  1769 strings translated of the 10156 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/17)

# Maintainance mode
These [Magento2Translations](http://magento2translations.github.io/) packages are updated on a non-regular basis. We have a system in-place to do the updating automatically but running this is still a manual job and requires financial investment to automate.
This means that from time to time we will run the sync and build from Crowdin. If you would like to assist please send us a message.

Magento has started the [Magento Localization](https://github.com/magento-l10n) Community Engineering Project to facilitate translating Magento2.
In the future we might decide to merge this project with [Magento Localization](https://github.com/magento-l10n).
If they have a similar language pack to this one you can find it [here](https://github.com/magento-l10n/language-mk_MK).

Or have a look at all the other great community maintained packages at [e-conomix/magento-translations](https://github.com/e-conomix/magento-translations) and [Mageplaza maintained packages](https://github.com/mageplaza?q=language).

# Installation
**Please select the git branch appropriate for your magento version from this repo.**
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_mk_mk:2.2.4-dev
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_mk_mk/archive/2.2.4.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_mk_mk`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/mk_MK/mk_MK.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Macedonian (North Macedonia)*'

# Contribute
To help push the '*Macedonian (македонски) Magento2 Language Pack (mk_MK)*' forward please goto [this](https://crowdin.com/project/magento-2/mk) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).
