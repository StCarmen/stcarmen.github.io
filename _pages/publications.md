---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<p style="font-size: 0.85em; color: #7a8288; font-style: italic; margin: 0.5em 0 1.2em 0; padding-left: 0.3em; border-left: 3px solid #d3d3d3;">* indicates equal contribution</p>

{% include base_path %}
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
