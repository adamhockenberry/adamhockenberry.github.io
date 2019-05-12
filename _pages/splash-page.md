---
title: "Splash Page"
layout: splash
title: "<br/>"
author_profile: true
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.0"
  overlay_image: ../images/splash-headline.jpg
  actions:
    - label: "Download"
      url: "https://github.com/mmistakes/minimal-mistakes/"
#  caption: "Photo credit that should be deleted maybe: [**Unsplash**](https://unsplash.com)"
excerpt: "<br/><br/><br/><br/><br/><br/>"
intro: 
  - excerpt: 'This webpage is a work in progress. Some of the above links work, but will get better over the coming weeks as I work through a thorough re-factoring of my site. Stay tuned!'
#feature_row:
#  - image_path: /assets/images/unsplash-gallery-image-1-th.jpg
#    alt: "placeholder image 1, ideally"
#    title: "Protein translation"
#    excerpt: "Producing proteins consumes ."
#  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
#    alt: "placeholder image 2"
#    title: "Cellular growth"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"
#  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
#    title: "Biological data science"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Protein structure and translation"
    excerpt: 'More to follow shortly'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Cellular growth"
    excerpt: 'something interesting here'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Biological data science"
    excerpt: 'Phylogenetic challneges'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row5:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "The importance of why"
    excerpt: 'excerpts to follow'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row5" type="center" %}
