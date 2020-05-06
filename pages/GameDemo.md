---
layout: page
title: 小游戏演示
titlebar: GameDemo
subtitle: <span class="mega-octicon octicon-cloud-download"></span>&nbsp;&nbsp;
     <a href ="https://blog.csdn.net/q764424567">更多精选文章 ， <font color="#EB9439">点我</font>查看！</a><br/><br/>
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
     <a href ="http://www.qq764424567.top/assets/images/itzy.jpg">关注公众号：<font color="#00FF00">恬静的小魔龙</font>，回复“大前端”进群交流。</a>
menu: Unity3D
css: ['blog-page.css']
permalink: /GameDemo
keywords: Unity3D,Unity3D开发小游戏，Unity3D插件，算法，SVN，C#，VR，PUN
---
<!--
<div class="row">
    <div class="col-md-12">
        <ul id="posts-list">
            {% for post in site.posts %}
                {% if post.category=='GameDemo' %}
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
        {% include pagination.html %}
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
-->
<style>
.Game{
		float:left;
        width: 520px;
        background: skyblue;
        border-radius: 30px;
        margin-left: 10px;
        /* 重点样式 */
        box-shadow: 1px 1px 1px 1px white;
		margin: 0 50px 20px 0;
		padding: 5px 20px 10px;
        outline: 10px solid white
}
.Game2{
		float:left;
        width: 520px;
        background: skyblue;
        border-radius: 30px;
        margin-left: 10px;
        /* 重点样式 */
        box-shadow: 1px 1px 1px 1px white;
		margin: 0 5px 20px 0;
		padding: 5px 20px 10px;
        outline: 10px solid white
}
</style>
<div class="Game">
<p>1、Unity3D开发《俄罗斯方块》游戏</p>
<p>截图：<br></p>
<p><img src="http://cdn.qq764424567.top/20200426181730.png" height="300px" width="481px"></p>
<p>教程：<br></p>
<p><a href="https://blog.csdn.net/q764424567/article/details/93622038">https://blog.csdn.net/q764424567/article/details/93622038</a></p>
<p>演示地址：<br></p>
<p><a href="http://www.qq764424567.top/Game_Tetris.html">http://www.qq764424567.top/Game_Tetris.html</a></p>
</div>

<div class="Game2">
<p>2、Unity3D开发《愤怒的小鸟》游戏</p>
<p>截图：<br></p>
<p><img src="http://cdn.qq764424567.top/1" height="300px" width="481px"></p>
<p>教程：<br></p>
<p><a href="https://blog.csdn.net/q764424567/article/details/100726495">https://blog.csdn.net/q764424567/article/details/100726495</a></p>
<p>演示地址：<br></p>
<p><a href="http://www.qq764424567.top/Game_AngryBirds.html">http://www.qq764424567.top/Game_AngryBirds.html</a></p>
</div>
<div class="comment">
    {% include comments.html %}
</div>