# hexo-theme-sim

A brand new default theme for [Hexo].

- [Preview](http://hexo.io/hexo-theme-landscape/)

## Installation

### Install

``` bash
$ git clone https://github.com/mrzhangcc/hexo-theme-sim.git themes/hexo-theme-sim
```

**hexo-theme-sim requires Hexo 2.4 and above.**

### Enable

Modify `theme` setting in `_config.yml` to `hexo-theme-sim`.

### Update

``` bash
cd themes/hexo-theme-sim
git pull
```

## Configuration

``` yml
# Header
menu:
  主页: /
  技术: /category/technology
  散文: /category/prose
  菜谱: /category/cookbook
  关于: /about
rss: /atom.xml

# display widgets at the bottom of index pages (pagination == 2)
index_widgets:
# - category
# - tagcloud
# - archive

# widget behavior
archive_type: 'monthly'
show_count: false

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
fb_admins:
fb_app_id:
```

- **menu** - Navigation menu
- **rss** - RSS link
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
- **google_plus** - Google+ ID

## Features


## Development

### Requirements

- Hexo 3.3+
