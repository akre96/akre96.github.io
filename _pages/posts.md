---
layout: archive
title: "Posts"
permalink: /posts/
---

{% for post in site.posts limit: 5 %}
  [{{ post.title }}]({{post.url}})
{% endfor %}
