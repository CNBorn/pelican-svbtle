# Pelican-svbtle

This is a adaptation specified for [Tyler Xing's Blog](http://cnborn.net).

### BUILD

```bash
npm install less -g
make less
```

## SETTINGS.PY

These are the Pelican global variables currently supported by the theme:

- `GOOGLE_ANALYTICS`
- `DISQUS_SITENAME`
- `LINKS(('name1', 'url1'), ('name2', 'url2'))`
- `DEFAULT_DATE_FORMAT = ('%b %d, %Y')`: suggested date format
- `FEED_DOMAIN = SITEURL`

## PLUGIN SUPPORT

- `language` template for [pelican-langcategory](https://github.com/CNBorn/pelican-langcategory)

## MODIFICATION

- Accent color can be changed by editing `@accent` in `./static/css/style.less`.
- A different Pygmentize theme can be used by editing `./Makefile` and running `make pygments`.

## AUTHORS

William Ting, Tyler Xing, James Cooke

## LICENSE

Released under MIT License, full details in `LICENSE` file.
