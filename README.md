# Dusk

Dusk is a minimal dark theme for Hugo

## Get the theme

`git clone https://github.com/LordMathis/hugo-theme-dusk themes/dusk`

## Configure the theme

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

## Add content

Add your blog posts to `content/blog`. Add info about you to `about.md` in `content`