# Sanitizer Transliterate

A module for ProcessWire CMS/CMF. Adds a `transliterate` method to `$sanitizer` that performs character substitutions as defined in the module config.

## Usage

[Install](http://modules.processwire.com/install-uninstall/) the Sanitizer Transliterate module.

Customise the character replacements in the module config as needed.

Use the sanitizer on strings like so:

```php
$transliterated_string = $sanitizer->transliterate($string);
```

![transliterate](https://user-images.githubusercontent.com/1538852/54096964-01fdfa00-4413-11e9-97a0-a5004f45c0c4.png)
