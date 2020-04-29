# crispy-waffle

This site used this free and open-source Jekyll theme, [Agus Makmun](https://github.com/agusmakmun/agusmakmun.github.io/), as its starting point. That had bugs related to the path when you deploy it in GH pages, but was able to refer to [Panda Cookie](https://github.com/zemmyang/panda-cookie) for changes resolving that.


## Notes Based on Original README

### References

* [A simple grey theme for Jekyll](https://github.com/liamsymonds/simplygrey-jekyll) - Project that Agus Makmun was forked from
* [Super Search](https://github.com/chinchang/super-search) - Used for searching posts using titles and descriptions
* [https://agusmakmun.github.io](https://agusmakmun.github.io) - Demo site
* [Jekyll Compress HTML](https://github.com/penibelst/jekyll-compress-html) - Used to minify HTML

### Installation and Configuration

* [x] Fork this repository
* [x] Edit site settings in `_config.yml`
* [x] Edit about content in `about.md`
* [x] Change avatar in `static/img/avatar.jpg` (from Panda Cookie)
* [ ] Edit your projects at file of `projects.md`, `_data/projects.json` and inside path of `_project/` _(for detail project)_.
* [x] Edit categories inside `category/`
* [x] Clean up existing entries in `_posts/`

### How to Use

#### Add New Category

Create a corresponding file for the new category inside `category/`.

#### Add New Post

Create a corresponding file for the new post inside `_posts/` with filename format: `YYYY-MM-DD-slug-for-title.md`

Inside the file, include metadata.

```
---
layout: post                          # (required)
title: "Your Title"                   # (required)
date: 2016-04-20 19:51:02 +0700       # (required)
categories: [python, django]          # (custom) must have corresponding file in categories/
tags: [foo, bar]                      # (custom) tags only for meta `property="article:tag"`
image: Broadcast_Mail.png             # (custom) image only for meta `property="og:image"`, save your image inside path of `static/img/_posts`
---

# your content post with markdown syntax goes here...
```


### Installing in Local Environment

```
bundle install
jekyll serve  OR bundle exec jekyll serve
```

### Contributing to Agus Makmun

Feel free to [open a bug](https://github.com/agusmakmun/agusmakmun.github.io/issues) or [contribute to code](https://github.com/agusmakmun/agusmakmun.github.io/pulls)!
