---
layout: page
title: 所有的文章都在这里
titlebar: archives
subtitle: <span class="mega-octicon octicon-calendar"></span>&nbsp;&nbsp;专题系列： &nbsp;&nbsp; <a href ="http://www.qq764424567.top/Unity3D.html"><font color="#1A0DAB">Unity3D</font></a>&nbsp;&nbsp; <a href ="http://www.qq764424567.top/life.html"><font color="#EB9439">程序人生</font></a>&nbsp;&nbsp; <a href ="http://www.qq764424567.top/web.html"><font color="#1E90FF">文章分享</font></a>
menu: archives
css: ['blog-page.css']
permalink: /archives.html
---

<ul class="archives-list">
  {% for post in site.posts %}

    {% unless post.next %}
      <h3>{{ post.date | date: '%Y' }}</h3>
    {% else %}
      {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
      {% capture nyear %}{{ post.next.date | date: '%Y' }}{% endcapture %}
      {% if year != nyear %}
        <h3>{{ post.date | date: '%Y' }}</h3>
      {% endif %}
    {% endunless %}

    <li><span>{{ post.date | date:'%m-%d' }}</span> <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>