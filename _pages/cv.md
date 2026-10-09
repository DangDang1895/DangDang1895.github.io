---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. student, School of Future Technology, South China University of Technology, 2026 – present
  * Supervisor: [Prof. Cen Chen](https://www2.scut.edu.cn/ft/2022/0408/c45109a495443/page.htm)
* M.Eng. in Electronic Information, Qingdao Institute of Software, China University of Petroleum (East China), 2023 – 2026
  * Supervisor: [Dr. Chen Zhang](https://computer.upc.edu.cn/_s104/_t1903/2023/0727/c20896a409078/page.psp)

Research interests
======
* Embodied intelligence
* Machine learning, deep learning
* Federated learning

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
