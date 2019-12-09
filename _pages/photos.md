---
layout: archive 
permalink: /photos/
title: Photography
author_profile: false
sidebar:
  - image: "/assets/images/nature_collage.jpg"
description: "I am not a pro but avid photo shooter. Capturing the moments and cherishing them makes my busy life soother. It provides me opportunity to look back and enjoy watching those still moments and memories around them. "
toc: true
og_image: "/assets/images/nature_collage.jpg"
---
I am not a pro but avid photo shooter. Capturing the moments and cherishing them makes my busy life soother. It provides me opportunity to look back and enjoy watching those still moments and memories around them.

## Latest stories

<div class="grid__wrapper">
  {% assign collection = 'Photography' %}
  {% assign posts = site[collection] | reverse %}
  {% for post in posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>