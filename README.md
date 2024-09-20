# ZXTZ1111.github.io<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>复杂带图页面示例</title>
  <style>
    /* 全局样式设置 */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    /* 头部样式 */
    header {
      background-color: #333;
      color: white;
      padding: 20px;
	  text-align: center;
    }

    /* 导航栏样式 */
    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
    }

    nav ul li {
      display: inline;
      margin-right: 20px;
    }

    nav ul li a {
      text-decoration: none;
      color: white;
      transition: color 0.3s;
      /* 添加过渡效果 */
    }

    nav ul li a:hover {
      color: lightblue;
      /* 鼠标悬停时的颜色 */
    }

    /* 主要内容区域样式 */
    main {
      display: flex;
      padding: 20px;
    }

    /* 文章内容样式 */
    article {
      flex: 3;
    }

    /* 侧边栏样式 */
    aside {
      flex: 1;
      background-color: #f5f5f5;
      padding: 20px;
    }

    /* 页脚样式 */
    footer {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }
	  
	.banner {
	background-color: #070707;
	background-image: url();
	height: 400px;
	background-attachment: fixed;
	background-size: cover;
	background-repeat: no-repeat;
}
    .parallax {
	color: #CB171A;
	text-align: right;
	padding-right: 100px;
	padding-top: 110px;
	letter-spacing: 2px;
	margin-top: 0px;
}
	  .parallax_description {
	color: #D82225;
	text-align: right;
	padding-right: 100px;
	width: 30%;
	float: right;
	font-weight: lighter;
	line-height: 23px;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
	margin-left: 0px;
}
	
.footer_column {
	width: 50%;
	text-align: center;
	padding-top: 30px;
	float: left;
	color: #FFFFFF;
	transition: all 0.3s linear;
}
  </style>
</head>

<body>
	   <audio controls >
     <source src="华晨宇 _ 郎朗 - 好想爱这个世界啊 (Live).flac" type="audio/mpeg">
     Your browser does not support the audio element.
   </audio>
  <!-- 头部区域 -->
  <header>
    <h1>复杂带图页面示例</h1>
    <nav>
      <!-- 导航栏列表 -->
      <ul>
        <li><a href="#">首页</a></li>
        <li><a href="#">关于我们</a></li>
        <li><a href="#">产品服务</a></li>
        <li><a href="#">联系我们</a></li>
      </ul>
    </nav>
  </header>
  <!-- 主要内容区域 -->
  <main>
    <!-- 文章部分 -->
    <article>
      <!-- 文章标题 -->
      <h2>美丽的自然风光</h2>
      <!-- 段落描述 -->
      <p>今天是 2024 年 9 月 18 日，星期三。这是一个复杂的带图片页面示例，让我们一起欣赏美丽的自然风光。</p>
    
      <p>大自然赋予了我们无尽的美景，从壮丽的山脉到宁静的湖泊，从广袤的森林到绚丽的花海。</p>
    </article>
    <!-- 侧边栏部分 -->
    <aside>
      <img src="图片/微信图片_20240918205840.jpg" width="700" height="280">
    </aside>
	  
  </main>
	
	<section class="banner">
	  <div>
		  <a href="#">
	          <img src="../图库/170559101.jpg" alt=""  height="335" class="footer_column"/>
		  </a>
	  </div>
		<h2 class="parallax">PARALLAX HERO</h2>
	  <p class="parallax_description">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam</p>
</section>
  <!-- 页脚区域 -->
  <footer>
    <p>版权所有 © 2024 复杂带图页面示例。保留所有权利。</p>
  </footer>
</body>

</html>
```
