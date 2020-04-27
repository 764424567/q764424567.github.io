---
layout: page
title: Unity3D开发小游戏
titlebar: Game_AngryBirds
menu: Game_AngryBirds
subtitle:  <span class="mega-octicon octicon-person"></span>&nbsp;&nbsp; 恬静的小魔龙，程序猿一枚
css: ['about.css', 'sidebar-popular-repo.css', '../../bower_components/flag-icon-css/css/flag-icon.min.css']
permalink: /Game_AngryBirds
---

<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity3D 《愤怒的小鸟》游戏</title>
    <link rel="shortcut icon" href="/assets/Game/Game_AngryBirds/TemplateData/favicon.ico">
    <link rel="stylesheet" href="/assets/Game/Game_Tetris/TemplateData/style.css">
    <script src="/assets/Game/Game_AngryBirds/TemplateData/UnityProgress.js"></script>  
    <script src="/assets/Game/Game_AngryBirds/Build/UnityLoader.js"></script>
    <script>
      var gameInstance = UnityLoader.instantiate("gameContainer", "/assets/Game/Game_AngryBirds/Build/Game_AngryBirds.json", {onProgress: UnityProgress});
    </script>
  </head>
  <body>
    <div class="webgl-content">
	<div class="about">
		<span><h1><font color="#FF0000">Unity3D开发《愤怒的小鸟》游戏</font></h1></span><br>
		<span><h3><font color="#0000FF">操作说明：拉动小鸟弹弓，去射穿小猪吧</font></h3></span><br>
		<span><h3><font color="#AAAAFF">使用说明：加载比较慢，黑屏是正常，稍等一下就行了</font></h3></span><br>
	</div>
      <div id="gameContainer" style="width: 960px; height: 600px"></div>
      <div class="footer">
        <div class="webgl-logo"></div>
        <div class="fullscreen" onclick="gameInstance.SetFullscreen(1)"></div>
        <div class="title">全屏</div>
      </div>
    </div>
	<!-- Comments -->
    <div class="comment">
       {% include comments.html %}
    </div>
  </body>
</html>



