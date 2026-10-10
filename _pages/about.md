---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I received my master's degree from [China University of Petroleum (East China)](https://www.upc.edu.cn/) in 2026, and I am now a first-year Ph.D. student at the School of Future Technology, [South China University of Technology](https://www.scut.edu.cn/). My research focuses on embodied intelligence, and I am also interested in machine learning, deep learning and federated learning.

<h2>News</h2>

<ul class="news-list">
  <li><span class="news-date">2026.09</span> Paper published at IJCAI-26: <em>Revisiting Hypernetwork in Model Heterogeneous Personalized Federated Learning</em> (2nd author), with <a href="https://github.com/DangDang1895/MH-pFL">code</a> released.</li>
  <li><span class="news-date">2026.09</span> Started my Ph.D. at the School of Future Technology, South China University of Technology.</li>
  <li><span class="news-date">2026.06</span> Received my M.S. degree from China University of Petroleum (East China).</li>
</ul>

[Email](mailto:202610196897@mail.scut.edu.cn) / [Github](https://github.com/DangDang1895)

<h2>Publications</h2>

<ul class="pub-list">
  {% assign pubs = site.publications | sort: "date" | reverse %}
  {% for post in pubs %}
  <li>
    <strong>{{ post.title }}</strong><br />
    {{ post.citation | replace: "Husheng Li", "<strong>Husheng Li</strong>" }}<br />
    {% if post.paperurl %}<a href="{{ post.paperurl }}">Paper</a>{% endif %}{% if post.codeurl %} | <a href="{{ post.codeurl }}">Code</a>{% endif %}
  </li>
  {% endfor %}
</ul>
