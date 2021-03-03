# MijiaTemp string resources for translation

This project has the strings for the **MijiaTemp app** (get it from
[Google Play](https://play.google.com/store/apps/details?id=com.smrtprjcts.mijiabt) or
from [Aptoide](https://mijiatemp.en.aptoide.com/app)).

If you would like to improve an existing translation, please do it on github.

If you would like to create a new translation, you can choose from these methods:

## Git method (preferred)

Clone this repository or download the necessary XMLs (e.g. the default English) and translate them (see the app/src/main/res/values/ directory).
If you are using Android Studio it is easiest to open the Translations Editor

Steps: 
* Create a directory (app/src/main/res/values-\<lang\>) for the new translation e.g. values-hu for Hungarian, values-de for German, etc. The correct language code can be found in the ISO639-1 column [there](http://www.loc.gov/standards/iso639-2/php/code_list.php).
* Copy the available values directory content to your new directory. Translate the texts between > and < chars. Please pay attention to the special characters ( > < \n \" %s %.f etc) because non-proper strings can cause crashes.  

## POEditor method
POEditor has a 1000 strings limit. [Join to translate project.](https://poeditor.com/join/project/aBfzBj2DX6)
The languages that the app already contains are always removed from POEditor because of the above limitation so the further translations/corrections must be done here, at github.

P.S.: English strings are always up-to-date, that would be the better choice for translation base. 


Thanks for helping!
