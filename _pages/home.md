---
permalink: /
layout: splash
date: 2016-07-25T15:39:24+08:00
header:
  image: IMG_7912.jpg
  caption: "Highrise buildings in Western District, Hong Kong. Photo credit: Kelly Lui"
intro:
  - title: Kelly Lui
  - excerpt: 'Do not go gentle into that good night,</ br>  Old age should burn and rave at close of day;  Rage, rage against the dying of the light.'
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
    excerpt: 'Articles and commentary on topics of my interest, in cluding but not limited to Hong Kong, China, and political economy in general.'
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
    excerpt: 'In case you are interested in the source code of this website.'
    url: "https://github.com/kellylui321/kellylui321.github.io"
    btn_label: "View Source"
    btn_class: "btn--inverse"
---
{% include feature_row id="intro" type="center" %}
<hr noshade>
<hr noshade>
{% include feature_row %}
<hr noshade>
<hr noshade>

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}
