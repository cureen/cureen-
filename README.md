<!DOCTYPE html>
<html xmlns="http://www.kir/2017/xhtml">
<head>
<meta content="en-us" http-equiv="Content-Language" />
<meta content="text/html; charset=utf-8" http-equiv="Content-Type" />
<meta name="viewport" content="width=device-width, initial-scale=0.9">
<title id="title">  
<link rel="shortcut icon"
<link rel="shortcut icon" href="favicon.ico" />
<title id="title">  
<title id="title">  
</title>
<script type="text/javascript">
var d = new Date()
var time = d.getHours()
if (time < 24) 
{ 
document.getElementById("title").innerHTML="Good evening";
 }
 if (time < 19) 
{ 
document.getElementById("title").innerHTML="Good afternoon";
 } 
if (time < 12)
{ 
document.getElementById("title").innerHTML="Good morning";
 } 
if (time < 5) 
{
 document.getElementById("title").innerHTML="Stay up late again";
 } 
</script>
</head>
<style>
/*下方这句不动它，翻译开始*/
* {
	padding: 0;
	margin: 0;
}
body {
	text-align: center;
    background-image:url("https://wanyoo.files.wordpress.com/2017/02/wp-1486895729579.jpg") !important;
 /*可换上面的图片地址*/
    background-size: 100% !important;
    background-repeat: no-repeat;
 	background-color: #ffffff;
  /*可删上面的固定句语*/
}
img.smaller {
	width: 198px;
	height: 65px;
	max-width: 250px;
	animation: flipInX 4s;
	-webkit-animation: flipInX 4s
}
.logo {
	font-size: 2em;
	white-space: normal;
	word-wrap: break-word;
	text-decoration: none;
	color: #ffffff
}
#search_input {
	width: 100%;
	height: 40px;
	background-color: transparent;
	border: none;
	outline: 0;
	font-size: 16px;
	color: #000000;
}
.search_part {
	margin-bottom: 0px;
	margin-top: 0px;
}
.search_bar span {
	display: block;
	font-size: 12px;
	overflow: hidden;
	padding-left: 2px;
	margin-right: 42px;
	vertical-align: middle;
}
.search_bar span i {
	display:none;
	float: right;
	width: 35px;
	height: 40px;
	background: url(img/clear.png) no-repeat center;
	background-size: 16px;
}
.search_bar .si {
	margin: 0 38px 0 10px;
}
.search_bar {
	box-shadow: 0 0 5px rgba(70,70,40,.255);
	-webkit-animation: fadeIn 2.5s;
	animation: fadeIn 2.5s;
	background-color: #fff;
	border-radius: 3px;
	display: table;
	vertical-align: middle;
	width: 100%;
	height: 30px;
	max-width: 400px;
	margin: 10px auto;
	position: relative;
	z-index: 10;
}
#search_submit {
	outline: 2;
	height: 40px;
	float: right;
	color: #125;
	font-size: 16px;
	font-weight: 500;
	border: none;
	background-color: transparent;
	padding: 0 13px 0 13px
}
#content {
	width: 100%;
	text-align: center;
	padding-top: 15px;
	padding-bottom: 15px;
}
.box {
	-webkit-animation: fadeInDown 1s;
	animation: fadeInDown 1s;
	position: relative;
	display: inline-block;
	width: 70px;
	border: 0;
}
.box a {
	width: 80%;
	height: 80%;
	position: absolute;
	left: 0;
	top: 0;
}
.url {
	color: #A2B4BA;
	height: 1em;
	line-height: 0.5em;
	width: 70px;
	font-size: 0.75em;
	white-space: nowrap;
	overflow: hidden;
	margin: auto;
	-webkit-border-top-right-radius: 5px;
	-webkit-border-bottom-right-radius: 5px;
	text-overflow: ellipsis;
	-o-text-overflow: ellipsis;
	-ms-text-overflow: ellipsis;
	padding-top: 2px;
	padding-bottom: 5px;
}
.icon {
	width: 3em;
	height: 3em;
	max-width: 72px;
}
#app-items {
	width: 100%;
	max-width: 400px;
	margin: 0px auto;
	text-align: center;
	background-color: #fff;
	padding-top: 0px;
	padding-bottom: 15px;
}
.title {
    background-color: #eeeeee;
    font-size: 140px;
    height: 30px;
    line-height: 30px;
    padding: 0 10px 0 20px;
}
.shuxing {
    color: #90a4ae;
    font-size: 14px;
    height: 30px;
    line-height: 20px;
    padding: 0 10px 0 20px;
}
</style>
<br />
<br />
<br />
<br />
<br />
<iframe src="http://www.thinkpage.cn/weather/weather.aspx?uid=U5D9ADCCD9&cid=CHBJ000000&l=&p=SMART&a=1&u=C&s=12&m=2&x=1&d=0&fc=&bgc=&bc=&ti=0&in=0&li=" frameborder="0" scrolling="no" width="200" height="90" allowTransparency="true"></iframe>
<body>
</style>
<body>
<div id="content">
<div class="search_part">
<form id="search_form" onsubmit="return search()" class="search_bar">
<input type="image" id="search_submit" value="搜索"  src="https://wanyoo.files.wordpress.com/2017/02/wp-1486895493943.png">
<span><i id="clear" onclick="clear_seach()"></i><div class="si"><input class="search" type="text" value="" onkeyup="get_suggest()" onfocus="get_suggest()" onpaste="get_suggest()" autocomplete="off" id="search_input" placeholder="输入关键字(っ*´Д`)っ" ></div>
</form>
</div>
<br />
<div class="box">
<a href="folder://"></a>
<p><img class="icon" src="https://wanyoo.files.wordpress.com/2017/02/wp-1486894962248.png" ></p>
<p class="url">书签</p>
</div>
<div class="box">
<a href="history://"></a>
<p><img class="icon" src="https://wanyoo.files.wordpress.com/2017/02/wp-1486895048024.png" ></p>
<p class="url">足迹</p>
</div>
<div class="box">
<a href="http://m.jd.com/?ad_od=1&cu=true&utm_source=baidu-pinzhuan&utm_medium=cpc&utm_campaign=t_288551095_baidupinzhuan&utm_term=ba6fb982ce824f8382e493214bab3b10_0_e8641427506a426b9cab3f2c9228b572"></a>
<p><img class="icon" src="https://wanyoo.files.wordpress.com/2017/03/wp-1489886808270.png"></p>
<p class="url">购物</p>
</div>
<div class="box">
<a href="http://www.yidianzixun.com/"></a>
<p><img class="icon" src="https://wanyoo.files.wordpress.com/2017/02/wp-1486895000968.png" ></p>
<p class="url">资讯</p>
</div>
<div class="box">
<a href="http://m.huya.com/"></a>
<p><img class="icon" src="https://wanyoo.files.wordpress.com/2017/03/wp-1489886880100.png" ></p>
<p class="url">直播</p>
</div>
<div class="box">
<a href="http://m.iloveyoulong.com/"></a>
<p><img class="icon" src="https://wanyoo.files.wordpress.com/2017/02/wp-1486894993156.png" ></p>
<p class="url">导航</p>
</div>
<div class="box">
<a href="http://fanyi.sogou.com/?fr=wapsearch&pid=sogouwap"></a>
<p><img class="icon" src="https://wanyoo.files.wordpress.com/2017/02/wp-1486895017050.png" ></p>
<p class="url">翻译</p>
</div>
<div class="box">
<a href="http://m.quankan.tv/"></a>
<p><img class="icon" src="https://wanyoo.files.wordpress.com/2017/03/wp-1489886658221.png" ></p>
<p class="url">视频</p>
</div>
<div class="box">
<a href="http://clbox.sxl.cn/"></a>
<p><img class="icon" src="https://wanyoo.files.wordpress.com/2017/03/wp-1489886745854.png" ></p>
<p class="url">工具</p>
</div>
<div class="box">
<a href="http://m.chinacaipu.com/"></a>
<p><img class="icon" src= "https://wanyoo.files.wordpress.com/2017/03/wp-1489886794212.png"></p>
<p class="url">菜谱</p>
</div>
<script type="text/javascript">function search(){if(document.getElementById("search_input").value != ""){window.location.href = "http://m.baidu.com/s?ie=utf-8&rn=30&tn=baiduhome_pg&oq=%E5%BC%A0%E7%B1%BD%E6%B2%90&rsv_enter=0&wd=" + document.getElementById("search_input").value;document.getElementById("search_input").value = "";}return false;}</script>
</div>
<font color="#90a4ae">
<font size="6">―·❀·―
<table width="30" border="0"
<div id="yiyan">
<div class="shuxing"><script type="text/javascript" src="https://api.lwl12.com/hitokoto/main/get?encode=js&charset=utf-8"></script><div id="lwlhitokoto"><script>lwlhitokoto()</script></div>
</div>
<br>
</div>
</div>
<script type="text/javascript">
var last_kw = '';
var max_sug_len = 1; //搜索建议最短触发长度
//window.location.href = "http://m.baidu.com/s?ie=utf-8&rn=30&tn=baiduhome_pg&oq=%E5%BC%A0%E7%B1%BD%E6%B2%90&rsv_enter=0&wd=" + encodeURIComponent(document.getElementById("search_input").value);</script>
</body>
</html>
