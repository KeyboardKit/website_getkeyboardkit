---
layout: blog
title: Blog
permalink: /blog/

redirect_to: https://keyboardkit.com/blog
---

<h1>Blog</h1>

<div class="blog">
    {%- include kankoda/tags/list.html tags=site.tags -%}
    {%- include kankoda/blog/post-list.html posts=site.posts -%}
    {%- include kankoda/tags/scripts.html -%}
</div>