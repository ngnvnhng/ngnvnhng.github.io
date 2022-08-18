---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
header:
  overlay_image: ../images/image_system-network-connection-connected.jpg
  overlay_filter: 0.1 # same as adding an opacity of 0.5 to a black background
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
