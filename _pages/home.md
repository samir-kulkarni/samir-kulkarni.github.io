---
layout: splash
permalink: /
title: Samir Kulkarni
author_profile: false
header:
   overlay_color: "#0000FF"
   overlay_filter: "0.5"
   overlay_image: "/assets/images/samir_profile.jpg"
   cta_label: "About me"
   cta_url: "/about/"
excerpt: "A tech guy writing about technology, life and personal stuff."
description: "My name is Samir Kulkarni. I am not a pro but avid photo shooter. Capturing the moments and cherishing them makes my busy life soother. It provides me opportunity to look back and enjoy watching those still moments and memories around them. Same applies to tech world. All the good things in the past are foundation to my approach to embracing new technologies."
og_image: "/assets/images/samir_profile.jpg"
feature_collections:
  - image_path: /assets/images/tech_collage.jpg
    alt: "Collage of cover images of tech posts"
    title: "Technology"
    excerpt: 'Technologies that drive us <br> <br> '
    url: "/tech/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/nature_collage.jpg
    alt: "Collage of cover images of Photography posts"
    title: "Photography"
    excerpt: 'Things we do, emotions we feel and little everyday things that make us human.'
    url: "/photos/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/read_collage.jpg
    alt: "Collage of cover images of Good Reads posts"
    title: "Good Reads"
    excerpt: 'Something that I find good to read. <br> <br> '
    url: "/reads/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
## Latest stories

<div class="grid__wrapper">
  {% for post in site.posts limit:4 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

{% include feature_row id="feature_collections" %}
