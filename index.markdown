---
title: Markdown Presentation Example
author: Christopher Wellons
layout: default
---

{% for post in site.posts reversed %}
<section class="slide">
{{ post.content }}
</section>
{% endfor %}
