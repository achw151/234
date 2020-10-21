```css
*{
	box-sizing: border-box;
}
*{
	padding: 0px;
	margin: 0px;
}
/*背景*/
.bg{
	height: 755px;
	width: 1518px;
	background-image: url(../img/背景图_画板%201.png);
	background-repeat: no-repeat;
	background-size:100% 100%;
	background-position: center;
}

/*主体*/
.bod{
	position: relative;
	height: 680px;
	width:1200px;
	border-radius: 25px;
	background-color: white;
	margin: auto;
	top: 38px;
}
/*图片设置*/
.im1{
	position: relative;
	margin-left: 10px;
	margin-right: 10px;
	top: 40px;
	height: 80px;
	width: 80px;
}
.im2{
	position: relative;
	margin-left: 20px;
	margin-right: 10px;
	bottom: -230px;
	height: 80px;
	width: 80px;
}
.im1 img{
	height: 80px;
}
.im2 img{
	height: 60px;
}
.im3{
	height: 20px;
}
.ima{
	display: inline-block;
	margin-bottom: 0px;
	margin-right: 10px;
	float: right;
	width: 22px;
	height: 22px;
}
/*导航*/
.nav{
	position: relative;
	display: inline-block;
	margin-left: 20px;
	margin-right: 20px;
	height: 250px;
	width: 120px;
	bottom: -80px;
}
ul{
	list-style-type: none;
}
a{
	color: black;
	padding-left: 30px;
	padding-top: 3px;
	display: block;
	text-decoration: none;
	height: 36px;
	width: 120px;
	background-color: white;
	margin-bottom: 20px;
	border-radius: 10px;
}
a.one{
	background-image: url(../img/人员图标.png);
	background-position: 0% 5%;
	background-repeat: no-repeat;
	background-size: 25px;
}
a.two{
	padding-top: 5px;
	background:#59CAE7 url("../img/数据(白色).png");
	background-position: 0% 20%;
	background-repeat: no-repeat;
	background-size: 25px;
}
a.three{
	background-image: url(../img/今日任务.png) ;
	background-position: 0% 5%;
	background-repeat: no-repeat;
	background-size: 26px;
}
a.four{
	background-image: url(../img/时钟%20实心.png);
	background-position: 0% 5%;
	background-repeat: no-repeat;
	background-size: 27px;
}
a.five{
	background-image: url(../img/齿轮.png);
	background-position: 0% -20%;
	background-repeat: no-repeat;
	background-size: 28px;
}
a.nor{
	display: inline-block;
	height: auto;
	width: auto;
	padding: 0px;
	color: rgb(88,202,230);
	font-weight: 530;
}
/*数据区*/
.date{
	display: flex;
	flex-wrap: wrap;
	align-content: flex-start;
	position: relative;
	height: 93%;
	width: 65%;
	padding: 30px 50px;
	background-color: rgb(246,247,251);
	top: -380px;
	left: 170px;
}
.ss{
	display: inline-block;
	height: 46px;
	width: 330px;
	padding-top: 4px;
	margin-right: 180px;
	border-radius: 15px;
	border: 0px;
	background-image: url(../img/查找.png);
	background-repeat: no-repeat;
	background-size:20px;
	background-position: 95% 50%;
}
.add{
	display: inline-block;
	height: 44px;
	width: 160px;
	padding-top: 9px;
	border-radius: 15px;
	border: 2px solid rgb(105,201,215);
	background-color: rgb(246,247,251);
	text-align: center;
	color: rgb(105,201,215);
}
.medi{
	display: inline-block;
	height: 110px;
	width: 330px;
	padding-top: 10px;
	padding-left: 20px;
	margin-top: 30px;
	margin-right: 50px;
	border-radius: 15px;
	border: 0px;
	color: white;
	background-image: url(../img/药.png);
	background-repeat: no-repeat;
	background-size:100% 100%;
	background-position: center;
}
.rp{
	display: inline-block;
	height: 110px;
	width: 100px;
	padding-top: 10px;
	padding-left: 20px;
	margin-top: 30px;
	margin-right: 30px;
	border-radius: 15px;
	border: 0px;
	background-color: white;
	background-repeat: no-repeat;
	background-size:100%;
	background-position:7% 88%;
}
.rp.r{
	color: rgb(251,136,133);
	background-image: url(../img/3.png);
}
.rp.p{
	color: rgb(105,201,215);
	background-image: url(../img/4.png);
}
.pa{
	display: inline-block;
	height: 60px;
	width: 193px;
	padding-top: 7px;
	padding-left: 60px;
	margin-top: 25px;
	margin-right: 30px;
	border-radius: 15px;
	border: 0px;
	color: white;
	background-image: url(../img/心率.png);
	background-repeat: no-repeat;
	background-size:37px;
	background-position: 10% 50%;
}
.pa.a{
	background-color: rgb(251,136,133);
	background-image: url(../img/心率.png);
}
.pa.n{
	background-color: rgb(255,181,92);
	background-image: url(../img/人员.png);
}
.pa.t{
	margin-right: 0px;
	background-color: rgb(105,201,215);
	background-image: url(../img/任务清单.png);
}
.week{
	display: inline-block;
	height: 245px;
	width: 380px;
	padding-top: 7px;
	padding-left: 30px;
	padding-right: 0px;
	margin-top: 25px;
	margin-right: 30px;
	border-radius: 15px;
	border: 0px;
	background-color: white;
}
.pro{
	display: inline-block;
	height: 245px;
	width: 230px;
	padding-top: 7px;
	padding-left: 30px;
	margin-top: 25px;
	border-radius: 15px;
	border: 0px;
	background-color: white;
}
.p1{
	display: inline-block;
	color: #f1f1f1;
	width: 20px;
	margin-top: 5px;
	line-height: 27px;
}
.r1{
	padding-left: 20px;
	margin-bottom: 4px;
	background-image: url(../img/lv.png);
	background-repeat: no-repeat;
	background-size:20px;
	background-position: 0% 50%;
}

/*用户信息*/
.user{
	position: absolute;
	width: 200px;
	height: 350px;
	right: 15px;
	top: 45px;
}
.pho{
	position: absolute;
	top: 405px;
	right: 15px;
	width: 220px;
	height: 90px;
	border-radius: 20px;
	background-image: url(../img/相机.png) ;
	background-position: 4% 50%;
	background-repeat: no-repeat;
	background-size: 50px;
	padding-left: 62px;
	box-shadow: 0px 0px 20px 7px rgb(210,210,210);
}
.noti{
	position: absolute;
	top: 525px;
	right: 15px;
	width: 200px;
	height: 20px;
}
.noti1{
	position: absolute;
	background-color: rgb(105,201,215);
	color: white;
	font-size: 15px;
	padding-left: 10px;
	padding-top: 20px;
	top: 565px;
	right: 15px;
	width: 200px;
	height: 75px;
	border-radius: 15px;
	z-index: 1;
}
.mm{
	position: absolute;
	background-color: rgb(251,136,133);
	top: 557px;
	right: 29px;
	width: 21px;
	border-radius: 20px;
	border: 2px solid white;
	z-index: 2;
}
```
```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>pro2</title>
		<link rel="stylesheet" type="text/css" href="css/new_file.css" />
	</head>
	<body>
		<div class="bg">
			<div class="bod">
				<div class="im1"><img src="img/创可贴.png"></div>
				<div class="nav"><ul>
					<li><a href="#" class="one">Patients</a></li>
					<li><a href="#" class="two">Overview</a></li>
					<li><a href="#" class="three">Histories</a></li>
					<li><a href="#" class="four">Appoinments</a></li>
					<li><a href="#" class="five">Setting</a></li>
				</ul></div>
				<div class="im2"><a href="#" class="nor"><img src="img/电话.png"></a></div>
				<div class="date">
					<form style="display: inline-block;height: 46px;width: 300px;margin-right: 140px;">
						<input type="text" placeholder="&nbsp;&nbsp;&nbsp;Searching something..." class="ss"/>
					</form>
					<div class="add">
						<p>+&nbsp;Add&nbsp;patient</p>
					</div>
					<div class="medi">
						<h3>Hi,Jennifer!</h3>
						<pre>

You've been doing your whole work plan for
the last two months.Way to go <img src="img/点赞.png" style="width: 10px;"></pre>
					</div>
					<div class="rp r">
						<h2>+11</h2>
						<p style="font-size: 12px;">reviews</p>
					</div>
					<div class="rp p">
						<h2>+78</h2>
						<p style="font-size: 12px;">patients</p>
					</div>
					<h3 style="margin-top: 18px;width: 100%;">Pantient&nbsp;analytics</h3>
					<div class="pa a">
						<p style="font-size: 14px;">Appoinments&nbsp;today</p>
						<p style="font-size: 12px;padding-top: 8px;">15&nbsp;patients</p>
					</div>
					<div class="pa n">
						<p style="font-size: 14px;">New&nbsp;patients</p>
						<p style="font-size: 12px;padding-top: 8px;">125&nbsp;for&nbsp;the&nbsp;month</p>
					</div>
					<div class="pa t">
						<p style="font-size: 14px;">Total&nbsp;patients</p>
						<p style="font-size: 12px;padding-top: 8px;">2000+</p>
					</div>
					<div class="week">
						<p style="display: inline-block;margin-bottom: 20px;"><b>This week's analytics overview</b></p>
						<div class="ima"><a href="#" class="nor"><img src="img/条形图.png" class="im3"></a></div>
						<div class="ima"><a class="nor" href="#"><img src="img/线条.png" class="im3"></a></div><br>
						<div class="p1"><p>25</p>
						<p>20</p>
						<p>15</p>
						<p>10</p>
						<p>5</p>
						<p>0</p></div>
						<img src="img/2.png" style="width: 300px;margin-top: 20px;"><br>
						<div class="p1" style="line-height: 4px;"><p style="font-size: 13px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Mon&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tue&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Wed&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Thu&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Fri&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sat&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sun</p></div>
					</div>
					<div class="pro">
						<p style="display: inline-block"><b>Progress</b></p>
						<div class="ima"><a class="nor" href="#" ><img src="img/刷新.png" class="im3"></a></div>
						<img src="img/1.png" style="width: 100px;margin-top: 20px;margin-left: 36px;">
						<ul>
							<li class="r1" style="background-image: url(img/lv.png);">Health</li>
							<li class="r1" style="background-image: url(img/hong.png);">Continue&nbsp;treamtment</li>
							<li class="r1" style="background-image: url(img/huang.png);">Neutral</li>
						</ul>
					</div>
				</div>
				<div class="user">
					<a href="#" class="nor" style="float: left;"><img src="img/叉.png"></a>
					<a href="#" class="nor" style="float: right;"><img src="./img/选项.png"></a>
					<img src="./img/头像.png" style="margin-left: 35px;margin-top: -10px; width: 130px;">
					<h2 style="text-align: center;margin-top: 15px;">Jennifer Turner</h2>
					<b><p style="text-align: center;margin-top: 20px;color: rgb(205,205,205);">Cardiologist</p></b>
					<b><p style="padding-top: 26px;display: inline-block;">Next&nbsp;event</p></b>
					<a href="#" class="nor" style="float: right; margin-top: 22px;">+&nbsp;Add</a>
				</div>
				<div class="pho">
					<a href="#" class="nor" style="color: #000000;"><pre style="font-size: 15px;padding-top: 10px;line-height: 25px;"><b>Medical conference
May 5 - 11:00 AM
<span style="color: rgb(211,211,211);">USA Houston</span></b></pre></a>
				</div>
				<div class="noti"><b><p>Next&nbsp;notifications</p></b></div>
				<div class="noti1"><pre>The patient will come to
you in 5 minutes.</pre></div>
				<a href="#"><img class="mm" src="img/X.png"></a>
			</div>
		</div>
	</body>
</html>
```
