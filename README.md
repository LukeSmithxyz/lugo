# Luke's Hugo Theme

A simple Hugo theme I plan on using for my personal website, [Based.Cooking](https://based.cooking) and [LandChad.net](https://landchad.net).

## get started

```sh
hugo new site new-site
cd new-site
git clone https://github.com/lukesmithxyz/lugo themes/lugo
echo "theme = 'lugo'" >> config.toml
cp themes/lugo/static/style.css static/
```

## stuff

- Makes one RSS feed for the entire site at `/index.xml`
- Stylesheet is in `/style.css`.
- If a post is tagged, links to the tags are placed at the bottom of the post.
- By default, the home index has its own custom file because I don't like it being a list. Remove `/layouts/index.html` if you want your home to function like a list as is default in Hugo.
