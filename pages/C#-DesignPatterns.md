---
layout: page
title: C#设计模式
titlebar: C#-DesignPatterns
subtitle: <span class="mega-octicon octicon-organization"></span>&nbsp;&nbsp; 微信搜索“恬静的小魔龙”，关注后回复“蔡徐坤”进群交流
menu: C#-DesignPatterns
css: ['blog-page.css']
permalink: /C#-DesignPatterns
---

<div class="row">

    <div class="col-md-12">

        <ul id="posts-list">
            {% for post in site.posts %}
                {% if post.category=='C#-DesignPatterns' %}
                <li class="posts-list-item">
                    <div class="posts-content">
                        <span class="posts-list-meta">{{ post.date | date: "%Y-%m-%d" }}</span>
                        <a class="posts-list-name bubble-float-left" href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
                        <span class='circle'></span>
                    </div>
                </li>
                {% endif %}
            {% endfor %}
        </ul> 

        <!-- Pagination -->
        {% include pagination.html %}

        <!-- Comments -->
       <div class="comment">
         {% include comments.html %}
       </div>
    </div>

</div>
<script>
    $(document).ready(function(){

        // Enable bootstrap tooltip
        $("body").tooltip({ selector: '[data-toggle=tooltip]' });

    });
</script>
