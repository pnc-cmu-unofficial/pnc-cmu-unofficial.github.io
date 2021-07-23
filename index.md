---
layout: default
title: Home
permalink: /
redirect_from:
    - /home
---
Welcome to the **unofficial** student run home page of the Ph.D. Program in Neural Computation (PNC) at Carnegie Mellon University. This page aggregates tribal knowledge that can improve the graduate school experience for PNC students by helping them better navigate the PNC, as well as life in Pittsburgh. If you would like to contribute new content or improve existing resources on any topic, please reach out via the email address below. 

<div class="notes">
<ul>
  {% assign ordered_pages = site.notes | sort:"order_number" %}
  {% for post in ordered_pages %}
    <article class="post">
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> (Last Update: {{post.updated}})</li>
    </article>
  {% endfor %}
</ul>
</div>