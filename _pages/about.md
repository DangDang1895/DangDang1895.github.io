---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I received my master's degree from [China University of Petroleum (East China)](https://www.upc.edu.cn/) in 2026, and I am now a first-year Ph.D. student at the School of Future Technology, [South China University of Technology](https://www.scut.edu.cn/). My research focuses on embodied intelligence, and I am also interested in machine learning, deep learning and federated learning.

[Email](mailto:202610196897@mail.scut.edu.cn) / [Github](https://github.com/DangDang1895)

<h2>Publications</h2>

<ul>
  {% assign pubs = site.publications | sort: "date" | reverse %}
  {% for post in pubs %}
  <li>
    <strong>{{ post.title }}</strong><br />
    {{ post.citation | replace: "Husheng Li", "<strong>Husheng Li</strong>" }}<br />
    {% if post.paperurl %}<a href="{{ post.paperurl }}">Paper</a>{% endif %}{% if post.codeurl %} | <a href="{{ post.codeurl }}">Code</a>{% endif %}
  </li>
  {% endfor %}
</ul>
