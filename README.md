# Klei Accounts Locale

This project contains the language localization files used to translate different elements in the user interface of the [Klei Accounts website](https://accounts.klei.com/). The localization files are simple text files using the [INI file format](https://en.wikipedia.org/wiki/INI_file) with a basic structure composed of sections, properties, and values.

## File Format

The basic element contained in a localization file is the key or property. Every key has a name and a value, delimited by an equals sign. The name appears to the left of the equals sign. The value appears to the right of the equals sign and is usually surrounded by [double quotes](https://en.wikipedia.org/wiki/Quotation_mark), this allows for explicit declaration of whitespace, and/or for quoting of special characters (equals, semicolon, etc.).

```ini
name = "value"
```

Semicolons (`;`) at the beginning of the line indicate a comment. Comment lines are ignored by the website and are merely used to leave notes about the keys below them. These notes may explain the context in which the key is used. Some comments also explain the usage of some pseudo-variables used to replace dynamic content.

```ini
; key “FollowUsButton” will be used inside one or more buttons that will
; allow the user to follow our social media accounts. The pseudo-variable
; <1></1> will be automatically replaced by the name of the social network.
; https://accounts.klei.com/account/rewards
FollowUsButton = "Follow us on <1></1> to receive updates"
```

## Case Insensitivity

Property names are not [case sensitive](https://en.wikipedia.org/wiki/Case_sensitive), but please leave them as they are for consistency.</small>

## Contributions

If you would like to contribute corrections, translations, or notes to the project please do so in the form of Git merge requests. If you do not know what Git is or need to refresh your memory, here is a tutorial that explains [How to Create a Pull-Request on GitHub](https://help.github.com/en/articles/creating-a-pull-request).
