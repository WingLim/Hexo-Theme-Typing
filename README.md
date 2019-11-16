# Hexo-Theme-Typing
A Simple Hexo Theme

## Install
1. Download theme files
```bash
git clone https://github.com/WingLim/Hexo-Theme-Typing.git themes/Typing
```
2. Use theme
```yaml
# <hexo root>/_config.yml
theme: Typing
```

3. Configure theme

Notice: There have a lang setting in `Tping/_config.yml` , set html lang in it rather than in `<hexo root>/_config.yml` .

Because if you set 'zh-cn' language in `<hexo root>/_config.yml` , the post generator will generate Chinese date style such as '十一月'.


```yaml
# Typing/_config.yml
# Custom favicon name
favicon: favicon.png

# Page languagge
lang: zh-cn

# Keyword for SEO
keywords: "Typing"

# Separate Post title and Blog title
separator: '|'

# Index Nav menu
menu:
  Archives: /archives
  About: /about

# Index GitHub Link
github:
  name:
  link:

# Footer infomation
footer:
  copyright:
  author:
```

## TODO

[ ] Lazy load image

[x] Optimizate SEO

[ ] Comment