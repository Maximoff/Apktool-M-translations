# Apktool-M-translations
Файлы локализаций Apktool M.

Пожалуйста, используйте встроенный переводчик Apktool M, или исправляйте вручную следующие символы:
1. `<` на `&lt;`.
2. `&` на `&amp;`.
3. `"` на `\"`.
3. `'` на `\'`.
4. символ `%` должен быть двойным `%%`, если он не используется для форматирования строки, или у строки должен быть атрибут `formatted="false"`.

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
search_menu_title
status_bar_notification_info_overflow
```

## For English
Apktool M localization files.

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
search_menu_title
status_bar_notification_info_overflow
```