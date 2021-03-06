lindsay-loinaka (Stacey Version)
================================

A [Stacey][st] theme for sparanoid.com, Codename lindsay-koinaka, version 14. Looking for WordPress version? Go [here][lk].


Installation
------------

1. For basic installation of Stacey, go [here][st].


More Setup / Tweaking / Things You Should Know
----------------------------------------------

1. A list of files you can modify:
    1. [`_shared.txt`][f13] - Change default settings to yours.
    2. [`latest.html`][f14] - Choose which post to display on index in this file.
    3. [`footer.html`][f11] - you can delete this if you don't know who is lindsay wu.
	4. [`sponsor.html`][f12] - Used for my own ad sponsor. Delete it or just modify it to yours.
    5. There're some page templates in the package names that begin with `page-`. You can modify them.
2. By default, the 'About' page is using a dark color version, based on what `persona` string you define to it, change it in *.txt and add your own styles
3. You'd better upload your image with min-with 1200px, if it must be smaller, apply a `class=center` on `img` tag.
4. For Chinese users:
    1. `#decoration` 如果出現中文字符會非常的醜陋，解決方案：
        1. 訪問 webfonts.fonts.com 並申請帳號，其中有可供嵌入的中文字型，例如 `M Banquet Simplified Chinese™ Medium`。
        2. 不使用中文標題。
        2. 禁用此樣式。
    2. 最好不要在标题使用简体中文字体，在 Mac 下效果很烂。
    3. 如果你的导航用的也是中文，你需要将 `.nav.pages` 的 `font-size` 值加大才能获得更好的显示效果。


Contributing
------------

1. Fork it
2. Create a branch (`git checkout -b my-lindsay-koinaka`)
3. Commit your changes (`git commit -am "Added new features"`)
4. Push to the branch (`git push origin my-lindsay-koinaka`)
5. Create an [Issue][1] with a link to your branch
6. Or just make a Pull Request from your branch
7. Enjoy a refreshing Diet Coke and wait


License
-------

Copyright (c) 2010 Tunghsiao Liu. 
Except Stacey which is (c) Anthony Kolber (see `LICENSE` for details). PHP Markdown Extra which is (c) Michel Fortin (see `/app/parsers/markdown-parser.inc.php` for details).


[f11]: https://github.com/sparanoid/sparanoid.com/blob/master/templates/partials/footer.html
[f12]: https://github.com/sparanoid/sparanoid.com/blob/master/templates/partials/sponsor.html
[f13]: https://github.com/sparanoid/sparanoid.com/blob/master/content/_shared.txt
[f14]: https://github.com/sparanoid/sparanoid.com/blob/master/templates/partials/latest.html
[1]: https://github.com/sparanoid/sparanoid.com/issues
[lk]: http://github.com/sparanoid/lindsay-koinaka
[st]: https://github.com/kolber/stacey