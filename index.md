---
layout: default
title: Home
permalink: /
redirect_from:
    - /home
---
Welcome to the **unofficial** student run home page of the Ph.D. Program in Neural Computation at Carnegie Mellon University. This page exists to provide PNC students easy access to tribal knowledge that can help them navigate the program as well as life in Pittsburgh. 

We welcome contributions from anyone with experiences and knowledge that can help PNC students have a better graduate school experience, both within and outside of the program. If you would like to contribute new content or improve existing resources, please reach out via the email address below.


<div class="notes">
<ul>
  {% for post in site.notes %}
    <article class="post">
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> (Last Update: {{post.updated}})</li>
    </article>
  {% endfor %}
</ul>
</div>