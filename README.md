# Nightfall

Nightfall is a minimal dark theme for Hugo

![Hugo Theme Nightfall](https://raw.githubusercontent.com/LordMathis/hugo-theme-nightfall/main/images/screenshot.png)
![Hugo Theme Nightfall Posts](https://raw.githubusercontent.com/LordMathis/hugo-theme-nightfall/main/images/screenshot_2.png)

## Get the theme

Import as [hugo module](https://gohugo.io/hugo-modules/use-modules/#use-a-module-for-a-theme) in `config.toml`:
```toml
[module]
[[module.imports]]
  path = 'github.com/LordMathis/hugo-theme-nightfall'
```

OR

Import manually:
1. `git clone https://github.com/LordMathis/hugo-theme-nightfall themes/nightfall`
2. Add `theme = "nightfall"` in your `config.toml`:

## Configuration

For full example chech `exampleSite/config.toml`

Add these params to you `config.toml`

```toml
[params]
author = "Mr Hugo"
user = "hello"
hostname = "gohugo.io"
```

You can also add social links

```toml
[[params.social]]
key = 0
name = "github"
url = "https://github.com/gohugoio"

[[params.social]]
key = 1
name = "twitter"
url = "https://www.example.com"

[[params.social]]
key = 2
name = "linkedin"
url = "https://www.example.com"

[[params.social]]
key = 3
name = "email"
url = "mailto:email@example.com"
```

To add a menu item add `[[menu.header]]` item to `config.toml`. For example:

```toml
[menu]
  [[menu.header]]
    name = "posts"
    weight = 0
    url = "/posts"
```
