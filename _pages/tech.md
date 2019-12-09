---
layout: archive 
permalink: /tech/
title: Technology
author_profile: false
sidebar:
  - image: "/assets/images/tech_collage.jpg"
description: "Technolgoies that helps to uncover our daily lives. "
toc: true
og_image: "/assets/images/tech_collage.jpg"
---
How technologies disrupts our lives and make impact on our day to day being. I will appreciate these technologies through short writings here.

## Latest stories

<div class="grid__wrapper">
  {% for post in site.categories.tech %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>