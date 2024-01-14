---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->


{% include base_path %}

<head>
  <style>
  a:link {
    color: black;
    background-color: transparent;
    text-decoration: none;
  }
  a:visited {
    color: black;
    background-color: transparent;
    text-decoration: none;
  }
  a:hover {
    color: #2E86C1;
    background-color: transparent;
    text-decoration: underline;
  }
  </style>
</head>

<body>

<h2>Journal</h2>

<ol>
  {% for post in site.publications reversed %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <a href="{{post.paperurl}}">[paper]</a>
      <!-- <a href="{{post.slidesurl}}" id="checkurl">[slides]</a>
      <a href="{{post.posterurl}}" id="checkurl">[poster]</a> -->
    </li>
  {% endfor %}
</ol>

<h2>Conference</h2>
<ol>
  {% for post in site.conferences reversed %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <a href="{{post.paperurl}}">[download]</a>
      <!-- <a href="{{post.slidesurl}}" id="checkurl">[slides]</a>
      <a href="{{post.posterurl}}" id="checkurl">[poster]</a> -->
    </li>
  {% endfor %}
</ol>

</body>
