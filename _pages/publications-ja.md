---
layout: archive
title: "論文"
permalink: /ja/publications/
author_profile: true
---
{% include base_path %}

[English](/publications/)

{% if author.googlescholar %}
論文リストは [Google Scholar profile]({{author.googlescholar}}) でもご覧いただけます。
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
