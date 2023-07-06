---
title: Title of Your Post
date: 2023-07-05 10:44:00 +0200 YYYY-MM-DD HH:MM:SS +/-TTTT
# +/-TTTT is the timezone, Europe/Zurich would be +0200
authors: [AuthorKey1, AuthorKey2]
# You can add yourself as author in /_data/authors.yml
image:
    path: "assets/img/path/to/image.png"
# Preview image of the post
img_path: "/"
# Default image path that will be prepended to all images
ref: "{{site.url}}/{{page.url}}/"
# Reference variable for links
pin: false
# Whether a post is pinned, omission means false
categories: [Main Category, Sub Category]
# 
tags: [tag1, tag2]
# tags are always lowercase
---

# Syntax Examples

Pretty much everything works as in normal markdown. 

Sections can be referenced with [{{ref}}]({{ref}}#syntax-examples). If the section name contains spaces, just replace them with "-".



Images can be floated with appending {: .right} or {: .left}



Footnotes [^footnote_id] can be added as well.

[^footnote_id]: this is the footnote

## 
