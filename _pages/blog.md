---
layout: archive
title: "Blog"
permalink: /blog/
---

{% for post in site.posts limit: 5 %}
  [{{ post.title }}]({{post.url}})
{% endfor %}
