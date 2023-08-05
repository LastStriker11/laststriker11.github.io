---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

Check if it works


{% include base_path %}

<body>

<!-- Uncomment the following when anything is available -->
{% for post in site.news reversed %}
  {% include archive-single.html %}
{% endfor %}

</body>

