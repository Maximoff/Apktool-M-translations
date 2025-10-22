# Apktool-M-translations
Пожалуйста, удаляйте по возможности из `strings.xml` строки с именами, начинающимися на `"abc_..."`, они не нужны.
Так же не нужно переводить строки с именами:
```
beta
dot
rarrow
lock_icon
block_icon
clock_icon
list_icon
prev_icon
next_icon
search_menu_title
status_bar_notification_info_overflow
```

## For English
Apktool M localization files.

To send me a change request you need to do the following:
1. fork this repository;
2. clone your fork to your device;
3. make your edits;
4. save and submit a pull request to my branch;

[GitHub documentation](https://help.github.com/articles/using-pull-requests/ "GitHub documentation")

Please use Apktool M's built-in translator, or manually correct the following characters:
1. `<` to `&lt;`.
2. `&` to `&amp;`.
3. `"` to `\"`.
3. `'` to `\'`.
4. the `%` character must be a double `%%` if it is not used to format the string, or the string must have a `formatted="false"` attribute.

Please delete strings with names beginning with `"abc_..."` from `strings.xml` if possible, they are not needed.
Also strings with names don't need to be translated:
```
beta
dot
rarrow
lock_icon
block_icon
clock_icon
list_icon
prev_icon
next_icon
search_menu_title
status_bar_notification_info_overflow
```
