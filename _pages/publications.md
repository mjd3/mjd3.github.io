---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my publications on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign show_preprints = false %}
{% for post in site.publications %}
  {% if post.type == 'preprint' %}
    {% assign show_preprints = true %}
    {% break %}
  {% endif %}
{% endfor %}

{% if show_preprints %}
---
<div align="center"><h1>Preprints</h1></div>
---
{% for post in site.publications reversed %}
  {% if post.type == 'preprint' %}
    {% include archive-single.html type="mylist" %}
  {% endif %}
{% endfor %}
{% endif %}

---
<div align="center"><h1>Journal Papers</h1></div>
---
{% for post in site.publications reversed %}
  {% if post.type == 'journal' %}
    {% include archive-single.html type="mylist" %}
  {% endif %}
{% endfor %}

---
<div align="center"><h1>Conference Papers</h1></div>
---
{% for post in site.publications reversed %}
  {% if post.type == 'conference' %}
    {% include archive-single.html type="mylist" %}
  {% endif %}
{% endfor %}
