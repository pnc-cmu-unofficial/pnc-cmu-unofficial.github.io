---
layout: default
title: Home
permalink: /
redirect_from:
    - /home
---
Welcome to the **unofficial** student run home page of the Ph.D. Program in Neural Computation (PNC) at Carnegie Mellon University. The purpose of this page is to provide PNC students with easy access to tribal knowledge that can improve that graduate school experience by helping them navigate both the PNC as well as life in Pittsburgh. If you would like to contribute new content or improve existing resources, please reach out via the email address below. 

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