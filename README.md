# Oliver's Hugo Theme

Fork of [lugo](https://github.com/LukeSmithxyz/lugo). Used for my personal website(s).

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
