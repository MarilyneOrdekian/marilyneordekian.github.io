---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find a full, up-to-date list of my articles on [my Google Scholar profile]({{ site.author.googlescholar }}).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
