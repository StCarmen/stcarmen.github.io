---
layout: archive
title: "Tianjing Zeng Homepage"
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
  - /aboutme
  - /_pages/about
---

{% include base_path %}

## About Me

I am a researcher at the Institute for Intelligent Computing, Alibaba Group. I received my M.S. and B.S. degrees from Renmin University of China in 2023 and 2020, respectively, under the supervision of Professor [Zhewei Wei](https://weizhewei.com/).

<span style="color:green">If you have any questions regarding my work or are interested in collaborating with me, please contact me via email. </span>

### Contact information
Email: zengtianjing.ztj@alibaba-inc.com

Wechat: StCarmen

## Research interests

My interest lies in Streaming algorithms and AI for databases (AI4DB) algorithms.  Currently, my focus is on intelligent databases and their associated algorithms and systems.

## Publications

<p style="font-size: 0.85em; color: #7a8288; font-style: italic; margin: 0.5em 0 1.2em 0; padding-left: 0.3em; border-left: 3px solid #d3d3d3;">* indicates equal contribution</p>

<ul>{% for post in site.publications reversed %}
{% include archive-single-cv.html %}
{% endfor %}</ul>
