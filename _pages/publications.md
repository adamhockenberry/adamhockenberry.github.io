---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

An up-to-date listing of my publications can be found on [my Google Scholar page.](https://scholar.google.com/citations?hl=en&user=W5qqC2wAAAAJ&view_op=list_works&sortby=pubdate){:target="_blank"}


{% include base_path %}

{% for post in site.publications reversed %}
 {% include archive-single.html %}
{% endfor %}
