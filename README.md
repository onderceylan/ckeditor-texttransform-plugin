Text Transform Plugin for CKEDITOR
================================

A very simple plugin which provides transforming selected text to new cases. You can transform selected text to uppercase, lowercase or simply capitalize that text.

Available Transform Cases
-------------------------

* Transform Text to Uppercase: Convert letters to uppercase
* Transform Text to Lowercase: Convert letters to lowercase
* Transform Capitalize: Capitalize each word of selected text
* Transform Switcher: Loop through all cases

Internationalization
-------------------------

Currently plugin supports 2 languages.

* en
* tr

*Translations are welcomed.*

Usage
-------------------------

1. Define plugin in CKEDITOR config object.

        CKEDITOR.config.extraPlugins = 'texttransform';

2. Add transform buttons to your editor toolbar.

        CKEDITOR.config.toolbar = [
            { name: 'texttransform', items: [ 'TransformTextToUppercase', 'TransformTextToLowercase', 'TransformTextCapitalize', 'TransformTextSwitcher' ] }
        ];

3. Set your CKEDITOR language if you did not set it yet.

        CKEDITOR.config.language = 'en';

Demo
-------------------------

[View the live demo](http://jsfiddle.net/t99kV/3/) on jsFiddle.


Cheers
--------------------

Thanks to [CKeditor] [1] and [jsFiddle] [2] for their good work.

  [1]: http://ckeditor.com        "CKeditor"
  [2]: http://jsfiddle.net        "jsFiddle"
