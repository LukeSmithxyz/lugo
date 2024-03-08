# Lugo - a fork of Luke's theme

A basic hugo theme based off of [Luke Smith's](https://lukesmith.xyz) hugo theme. Quite a lot has been changed so it is barely a fork at this point.

## Get started

```sh
hugo new site new-site
cd new-site/
git submodule add https://git.oliveratkinson.net/Oliver/lugo themes/lugo
echo "theme = 'lugo'" >> config.toml
```

## Notes

- Makes one RSS feed for the entire site at `/index.xml`
- Stylesheet is in `/style.css` and includes some important stuff for partials.
