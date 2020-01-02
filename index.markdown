---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Arvin Chen An Existentialist
---
I shall store my photos and blogs here from now on.
However, I have absolutely no idea what to do about it.
**Below are all of my blogs**
{% for post in site.post %}
  *[{{post.title}}]({{post.url}})
{% endfor %}