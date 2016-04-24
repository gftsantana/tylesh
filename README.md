Tylesh is a theme for the [Hugo](http://gohugo.io) static site generator.
It is designed to load fast and still have a lot of features.

## Installation

```bash
cd path/to/my/site/themes
git clone https://github.com/gftsantana/tylesh.git
```

## Configuration

### Basic configuration

The basic parameters you can use to personalize tylesh are:

- `author`
- `description`
- `metaTags`

An example `config.toml`:

```toml
baseurl = "http:\\example.com"
languageCode = "en-uk"
title = "My Example Website"
disqusShortname = "XYW"
theme = "tylesh"

[params]
  author = "Gildo Santana"
  description = "my awesome example website"
  metaTags = "example, examples, exemplification"
```


### Menus

Tylesh uses the built-in [Hugo menus system](http://gohugo.io/extras/menus/). It
currently cannot display multi-level menus.

There is a main navigation menu and a footer menu. They are defined in you config
file. An example `config.toml`:

```toml
[[menu.main]]
  name = "about hugo"
  weight = -110
  identifier = "about"
  url = "/about/"
[[menu.main]]
  name = "getting started"
  weight = -100
  identifier = "getting started"
  url = "/getting-started/"
[[menu.footer]]
  name = "pricing"
  weight = -110
  identifier = "pricing"
  url = "/pricing/"
[[menu.footer]]
  name = "work"
  weight = -100
  identifier = "work with us"
  url = "/work-with-us/"
```
### Social links

Tylesh displays a bar at the top of your site with links for your social networks,
defined in parameters. You should include the full URL in the configuration file:

```toml
baseurl = "http:\\example.com"
languageCode = "en-uk"
title = "My Example Website"
theme = "tylesh"

[params]
  author = "Gildo Santana"
  description = "my awesome example website"
  metaTags = "example, examples, exemplification"
  facebook = "https://www.facebook.com/McDonald"
  youtube = "https://www.youtube.com/user/bk"
  twitter = "https://twitter.com/SUBWAY"
  instagram = "https://www.instagram.com/kfc/"
  flickr = "https://www.flickr.com/people/25337230@N05/"
  github = "https://github.com/gftsantana"
  bitbucket = "https://bitbucket.org/astrojiudo/"
  linkedin = "https://linkedin.com/myLinkedin"
```
