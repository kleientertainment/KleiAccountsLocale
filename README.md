# Klei Accounts Locale

This project contains the language localization files used to translate different elements in the user interface of the [Klei Accounts website](https://accounts.klei.com/). The localization files are in [Gettext format](https://en.wikipedia.org/wiki/Gettext) which allows you to use a wide range of (free) software to translate the text.

Each file is named using the ISO 639-1 language code for the language it contains (e.g. en, de, fr, ru). If there are regional variations the two letter country code can be added after (e.g. fr-CA, pt-BR, zh-TW).

## New Languages

To translate the website into a new language simply copy the `strings.po` file into a new directory. The name of the directory must be a valid [ISO 639-1 language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes). For example, if I want to add support for [Esperanto](https://en.wikipedia.org/wiki/Esperanto) I would create a directory `eo` because “eo” is the [ISO 639-1 Language Code for Esperanto](https://www.loc.gov/standards/iso639-2/php/langcodes_name.php?iso_639_1=eo). Then, I would copy `strings.po` inside this folder.

## Editing PO Files

We anticipate that some gnu.org translators will find this format odd or inconvenient, if they never happened to work with PO files before. Don’t worry, you will soon get accustomed to it. It is the established format for translations in the Free World, and if you have any problems, other translators will help you.

The most efficient way to edit a PO file is using a specialized PO editor, because each of them represents and treats gettext messages in a consistent and predictable way. It is possible to edit a PO file with an ordinary plain text editor, but extra effort would be necessary to make the result valid.

Here is a list of widely used PO editors we can recommend:

| Software | Notes |
|----------|-------|
[Emacs PO mode](http://www.gnu.org/software/gettext/manual/html_node/PO-Mode.html#PO-Mode) | Enable/disable it with `M-x po-mode RET`.
[Gtranslator](https://wiki.gnome.org/Apps/Gtranslator) | The GNOME PO editor.
[Lokalize](http://userbase.kde.org/Lokalize) | The KDE 4 editor.
[KBabel](https://directory.fsf.org/wiki/KBabel) | The KDE 3 editor. No longer supported, but might be available on some old systems.
[Poedit](http://www.poedit.net) | Another popular editor based on the wxWidgets graphical toolkit.
[po.vim](http://www.vim.org/scripts/script.php?script_id=2530) | ftplugin for the Vim editor. The best option for people who use Vim as their editor.

## Contributions

If you would like to contribute corrections, translations, or notes to the project, please do so in the form of Git merge requests. If you do not know what Git is or need to refresh your memory, here is a tutorial that explains [How to Create a Pull-Request on GitHub](https://help.github.com/en/articles/creating-a-pull-request).
