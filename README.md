# Sanitizer Transliterate

A module for ProcessWire CMS/CMF. Adds a `transliterate` method to `$sanitizer` that performs character replacements as defined in the module config. The default character replacements are based on the defaults from InputfieldPageName, but with uppercase characters included too.

## Usage

[Install](http://modules.processwire.com/install-uninstall/) the Sanitizer Transliterate module.

Customise the character replacements in the module config as needed.

Use the sanitizer on strings like so:

```php
$transliterated_string = $sanitizer->transliterate($string);
```

![transliterate](https://user-images.githubusercontent.com/1538852/54096964-01fdfa00-4413-11e9-97a0-a5004f45c0c4.png)
