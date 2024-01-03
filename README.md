# Site source

This is the source for my personal site. The template and style is largely
based off my [Jekyll theme](https://github.com/0undefined/jekyll-theme-console),
which is just a customized fork of
[jekyll-theme-console](https://github.com/b2a3e8/jekyll-theme-console).

I use zola as the static page generator, works pretty good ngl.

for development, use `zola serve`

When deploying,

```
zola build
zip -r nelin.zip public
scp nelin.zip nelin.dk:~
ssh nelin.dk unzip nelin.zip
ssh nelin.dk rm -rf /var/www/nelin.dk
ssh nelin.dk mv public /var/www/nelin.dk
```
