#Atom Localizations
===
Atom Localization provides translations for Atom Editor's menus.



###Supported Languages
- Bengali
- Chinese - Simplified
- Chinese - Traditional
- Danish
- Dutch
- French
- German
- Japanese
- Portuguese - Brazilian


###Installation
- Please install through Atom->Preferences->Packages: localization
- Select your language through Packages->Localization


###Localization in your language
Any translation in languages not listed above are welcome, as well as better translation for those in list.

###How to localize
- Download [this json file](https://raw.github.com/pandarison/Atom-Localization/master/i18n/default.json) and replace "Your Translation" fileds.
- You can also add translations for other menu. Just follow the format.
- Put the file into /i18n under root directory of the package.
- Add your language name to languages.json under the root directory of the package. 
>{"language":"language name", "path":"../i18n/Your Translation.json"}
- Make a pull request to the repo, or send the file to <Pandarison@gmail.com>









###Release Notes
##### Version 1.2.0-1.4.0
* Add Portuguese - Brazilian Support. (By [Herbert](https://github.com/herberthudson))
* Add Dutch Support. (By [Reverp](https://github.com/Reverp/))

##### Version 1.0.0
* New configuration method

##### Version 0.12.0-0.15.0
* Add Japanese Support. (By [Odyssey](https://github.com/8bitodyssey), [kimama1997](https://github.com/kimama1997))
* Add French Support. (By NickMcFlies)
* Add German Support. (By [André](https://github.com/andrecedik))

##### Version 0.9.0-0.11.0
* Upgrade to Atom 0.72.0
* Add Danish Support. (By [Per](https://github.com/thedataking))

##### Version 0.8.0
* Remove old configuration when upgrade to new version

#####Version 0.3.0
* Fixed some bugs

#####Version 0.1.0
* Add Simplified Chinese Support
* Add Traditional Chinese Support
