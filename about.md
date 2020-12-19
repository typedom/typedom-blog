---
layout: page
title: About
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## About Dom
+ Software
    - Software Developer @ Metric Labs
    - Bachelor of Engineering (ICT: Software) @ UTS
+ Writing
    - Sometimes Copywriter @ Metric Labs
    - Written previously for CNET.com.au
+ Hobbyist Photographer

## About type dom
type dom is my little corner of the internet. It originally started as a blog that I’ve been writing in one iteration after another since 2007. Nowadays, it serves as a way to put down my thoughts about all the little big things in life.

+ Built on [Jekyll](https://jekyllrb.com)
   - Using [dactl](https://github.com/melangue/dactl)

## Contact Me
+ @typedom
+ typedom AT gmail

## Disclaimer
All original content on the site © Dominic Argente 2020.
All views expressed here are my own.
If you would like to use a photo or other content from this site, drop me a line.
</div>
