---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=wv3H-F4AAAAJ&hl=en">my Google Scholar profile</a>.</u>

Publications:  [2023](#2023), [2022](#2022), [2021](#2021)

<hr>

{% include base_path %}

### 2023

{% for post in site.publications reversed %}
  {%if post.pub_year == '2023' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

### 2022

{% for post in site.publications reversed %}
  {%if post.pub_year == '2022' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

### 2021

{% for post in site.publications reversed %}
  {%if post.pub_year == '2021' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
