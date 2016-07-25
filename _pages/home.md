---
permalink: /
layout: splash
date: 2016-07-25T15:39:24+08:00
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: IMG_7911.jpg
  caption: "Highrise buildings in Western District, Hong Kong. Photo credit: Kelly Lui"
excerpt: "Insert witty quote here."
intro:
  - excerpt: 'Insert *sweet* bio here.'
feature_row:
  - image_path: HK_2012.jpg
    alt: "placeholder image 1"
    excerpt: ' '
  - image_path: CapeTown_2016.jpg
    alt: "placeholder image 2"
    excerpt: ' '
  - image_path: DC_2015.jpg
    alt: "placeholder image 3"
    excerpt: ' '
feature_row2:
  - image_path: Georgetown_2015.jpg
    title: "Research"
    excerpt: 'Short articles and commentary on topics of my interest, in cluding but not limited to Hong Kong, China, and political economy in general.'
    url: "/research/"
    btn_label: "Read More"
    btn_class: "btn--inverse"
feature_row3:
  - image_path: Buildings.jpeg
    title: "Blog"
    excerpt: 'Travel journal, food, random musings.'
    url: "/blog/"
    btn_label: "Read More"
    btn_class: "btn--inverse"
feature_row4:
  - image_path: IMG_7911.jpg
    title: "Source"
    excerpt: 'View source'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
<center>Wanderlust</center>
{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}
