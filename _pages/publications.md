---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my publications on my <a href="{{site.author.googlescholar}}">Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<h2>Journal</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Conference</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Preprint</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'preprint' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

