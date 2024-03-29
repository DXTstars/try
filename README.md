<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<link type="text/css" rel="stylesheet" href="css/style.css" />
<title>Home</title>
</head>

<body>
<div class="wrapin"> 
  <!--头部-->
  <header>
    <ul class="nav clearfix">
        <img align="left" width="0" height="50" >
            <img align="right" width="0" height="50" >
            <li><a href="Home.html"><h2 class="white-text">Home</h2></a></li>
            <li><a href="Research.html"><h2 class="white-text">Research</h2></a></li>
            <li><a href="People.html"><h2 class="white-text">People</h2></a></li>
            <li><a href="Publication.html"><h2 class="white-text">Publication</h2></a></li>
            <li><a href="Gallery.html"><h2 class="white-text">Gallery</h2></a></li>
            <li><a href="News.html"><h2 class="white-text">News</h2></a></li>
            <li><a href="Contact.html"><h2 class="white-text">Contact</h2></a></li>
        </ul>
  </header>
 <div class="box">
			<div class="box-img"><img src="img1/a2.png" width="1000" height="160"/></div>
</div>
  
  <!--内容-->
  <div class="con">
  <div class="main-title">Home</div>
  <br><br>

<div class="box">
  <div class="box-img"><img src="img1/a1.png" width="1000" height="160"/></div>
</div>


<style>.title-container {
  position: flex; /* 使用绝对定位 */
  left: 25%; /* 将容器左边界设置在视口宽度的25%，即左半部分的中心 */
  

  width: 50%; /* 容器宽度设置为50%，保证标题不会超出左半部分 */
  text-align: center; /* 文本水平居中 */
}</style>

<br>
<div class="title-container">
  <h1>News</h1>
</div>

<br>


<style>
  #news-container {
      width: 50%;
      padding: 10px;
      box-sizing: border-box;
  }
  .news-item {
      margin-bottom: 20px;
      padding: 10px;
      border-bottom: 1px solid #ccc;
  }
  .hidden {
      display: none;
  }
  #show-more {
      cursor: pointer;
      color: blue;
      text-decoration: underline;
  }
</style>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</head>
<body>

<div id="news-container">
<!-- 显示前5条新闻 -->
<div class="news-item"><strong>Congratulations to the master's student Sun Yuchen on her first-author paper "Water Recovery from Wastewater by Hydrogels" being accepted by <i>Environmental Science & Technology Letters</i></strong></div>
<div class="news-item"><strong>Congratulations to the master's student Dong Xiuting on her first-author paper "Microbial Water Electrolysis Cells for Efficient Wastewater Treatment and H2 Production" being accepted by <i>ACS Sustainable Chemisrty & Engineering</i></strong></div>
<div class="news-item"><strong>A warm welcome to Academician Bruce Logan for visiting our research group!!!</strong></div>
<div class="news-item"><strong>Congratulations to Prof. Zhu for receiving support from the National Natural Science Foundation of China for the general program!!!</strong></div>
<div class="news-item"><strong>Congratulations to Prof. Zhu for winning the Gold Award of the "The 5th Young Scientist Award of the Chinese Society for Environmental Sciences"!!!</strong></div>

<!-- “更多”按钮 -->
<div id="show-more">show-more</div>
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script>
$(document).ready(function() {
  $('#show-more').click(function() {
      // 页面跳转到News页面
      window.location.href = 'News.html'; 
  });
});
</script>


<!-- Lab photo 界面 -->

<div class="tupian">
    <div class="title">
      <h1><center>Lab photo</center></h1>
    </div>
    <ul class="clearfix">
      <li><img src="img1/10.png"/></li>
      <li><img src="img1/8.png"/></li>
      <li><img src="img1/11.png"/></li>
      <li><img src="img1/12.png"/></li>
      <li><img src="img1/13.png"/></li>
      <li><img src="img1/14.png"/></li>
    </ul>
  </div>
</div>

 
<!--底部-->
<footer> 
  <h2 class="white-text">Water Treatment and Energy Recovery Research Group</h2>
  <h2 class="white-text">Welcome to join us!</h2>
  </footer>
</div>

</body>
</html>
