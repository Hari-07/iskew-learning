<template>
	<div id="banner">
			<div class = "top">
				<div class = "banner1date"><strong>09 - 12</strong>, NOV 2020</div>
				<div class = "heading1">
					<div><span class = "bannerquote"><i>iSkew Learning</i></span></div>
					<div><span class = "text1">Employability Skill</span></div>
					<div><span class = "text2">Development Workshop</span></div>
					<div><span class = "audience">For B. Tech S5 Batch Students</span></div>
				</div>
				<div class = "content1">
					<ul class = "list1">
						<li>Functional Skills</li>
						<li>Technical Skills</li>
						<li>Group Discussion</li>
					</ul>
					<ul class = "list2">
						<li>Personal Interview</li>
						<li>Goal Setting</li>
						<li>Resume Building</li>
					</ul>
				</div>
				<div class = "topdown">
					<span class="text3">Organised By,</span>
					<img src= "../../assets/GECLogo.png" class = "GEC"/>
					<span class="institute">
						<span>GOVERNMENT</span>
						<span>ENGINEERING</span>
						<span>COLLEGE, THRISSUR</span>
					</span>
				</div>
			</div>
			<div class = 'bottom'>
				<img class = "b1" src = "../../assets/iskew-white.png"/>
				<img class = "b2" src = "../../assets/IJG.png"/>
				<span class = "contact">
					<span class = "c1"><img src = "../../assets/globe.png"/>www.iskew.in</span>
					<span class = "c2"><img src = "../../assets/globe.png"/>iskewlearning@gmail.com</span>
				</span>
			</div>
	</div>
		<!-- <div class="banner3">
			<div class ="subbanner3">
				<div class="quoteBox3">
					<h1 class="bannerquote3">
						<div class="bannerbranding2">iSkew Learning</div>
						<span class="bannername"><i>TCS NQT</i></span><span><i>Mock Drill</i></span>
					</h1>
					<div class="bannersubquote3">OCTOBER 19 - 24th<a href="http://bit.ly/nqtmockdrill"><button class="enrollNow3">Enroll Now </button></a></div>
					<img src = '../../assets/Playbutton.png'/><span class="banner3vid">TCS NQT Placement Paper with Video Solutions</span>
				</div>
			</div>
		</div>
		<div class="banner1">
			<div class="quoteBox">
				<h1 class="bannerquote">
					<span style="color:#0089e2">TCS NQT Technical Training on C Programming</span>
				</h1>
				<div class="bannersubquote">Oct 19-21, 6-8pm <a href="https://forms.gle/dyYPskeoP8Hidu1i6"><button class="enrollNow">Enroll Now </button></a></div>
			</div>
			<img class="bannerimage" src="@/assets/gummy.png">
		</div> -->
</template>

<script>

export default {
	name:'Banner',
}
</script>

<style>


.top {
	overflow: hidden;
	background:#010a05;
	height: 40%; 
	padding: 1vw;
}

.banner1date{
	display: inline-block;
	color : #010a05;
	background: #eeebeb;
	vertical-align: middle;
	font-size: 1.3vw;
	margin-left: 76vw;
	line-height: 2;
	border-radius: 0.3vw;
}
.heading1{
	padding: 0;
	margin-bottom: 2vw;
}

.bannerquote{
	color : #010a05;
	background: #eeebeb;
	padding: 0.07vw;
	font-weight: bold;
	font-size: 1vw;
	border-radius: 0.3vw;
	margin-right: 70vw;
	line-height: 2;
}

.text1{
	color: #eeebeb;
	font-weight: bold;
	font-size: 2vw;
	margin-right: 59.5vw;
}

.text2{
	color: #eeebeb;
	font-weight: bold;
	font-size: 2vw;
	margin-right: 54vw;
}

.audience{
	color: #eeebeb;
	font-size: 1vw;
	margin-right: 64vw;
	line-height: 2;
}
.content1{
	float:left;
	margin-left: 20vw;
}

.list1{
	text-align: left;
	list-style-image: url('../../assets/bullet.png');
	color: #eeebeb;
	font-size: 1.2vw;
	display: inline-block;
	margin-right: 10vw;
}
.list2{
	text-align: left;
	list-style-image: url('../../assets/bullet.png');
	color: #eeebeb;
	font-size: 1.2vw;
	display: inline-block;
	margin-left: 0vw;
}
li{
	line-height: 2;
}

.topdown{
	margin-top: 1.5vw;
	float: left;
}
.text3{
	color: #eeebeb;
	font-size: 1.5vw;
	border-radius: 0.3vw;
	display: inline-block;
	margin-left: 40vw;
	margin-right: 3vw;
}

.GEC{
	height: 8vw;
	display: inline-block;
}

.institute
{
	margin-left: 4vw;
	vertical-align: middle;
	display: inline-block;
	width: 15vw;
}
.institute span
{
	line-height: 1.5;
	font-size: 1.5vw;
	float: left;
	color: #eeebeb;
}

.bottom {
	display: flex;
	overflow: hidden;
	position: relative;
	width:100%;
	background:#eeebeb;
	height: 6vw; 
}

.b1
{
	float:left;
	margin-left: 10vw;
	margin-right: 0vw;
	margin-top: 1vw;
	height: 4vw;
}
.b2
{
	float: left;
	margin-left: 3vw;
	margin-top: 1vw;
	height: 4vw;
}
.c1{
	margin-left: 40vw;
}
.c2{
	margin-left: 4vw;
}

.contact{
	font-size: 1vw;
	display: inline-block;
	margin-top: 2vw;
}
.contact img{
	height: 1.5vw;
	margin-right: 0.5vw;
}



/*.banner2{
	display: flex;
	position: relative;
	height: 35vw;
	background-image: url('../../assets/Batch3BG.jpg');
	background-repeat: repeat;
	background-origin: border-box;
	background-size: cover;
	overflow: hidden;
}
.banner3{
	display: flex;
	position: relative;
	height: 35vw;
	background-image: url('../../assets/NQT-Drill.jpg');
	background-repeat: repeat;
	background-origin: border-box;
	background-size: cover;
	overflow: hidden;
}

.bannerimage {
	height: 20vw;
	float: right;
	margin-top:4vw;
	margin-left: 17vw;
}

.quoteBox{
	text-align: left;
	margin-top:5vw ;
	margin-left: 8vw;
	min-width: 37vw;
}
.quoteBox2{
	text-align: left;
	margin-top:14vw ;
	margin-left: 8vw;
	min-width: 37vw;
}
.quoteBox3{
	text-align: left;
	margin-top:5vw ;
	margin-left: 8vw;
	min-width: 37vw;
}
.subbanner3{
	width: 100%;
	background-color: #ffffff;
	margin: 25px;
}

.bannerquote {
	font-weight: bold;
	color: #111111;
	font-size: 4vw;
}
.bannerquote2 {
	font-weight: bold;
	color: #111111;
	font-size: 4vw;
}
.bannerquote3 {
	font-weight: bold;
	color: #111111;
	font-size: 4vw;
	line-height: 1;
}
.bannerbranding {
	color: #0089e2;
	font-size: 2vw;
	font-style: italic;
	line-height: 1;
}
.bannerbranding2 {
	color: #000000;
	font-size: 2vw;
	font-style: italic;
	line-height: 2.5;
}
.bannersubquote{
	font-weight: bold;
	font-size: 1.8vw;
	font-style: italic;
}
.bannersubquote2{
	font-weight: bold;
	font-size: 1.8vw;
	color: white;
	margin-left: 29.5vw;
}
.bannersubquote3 {
	font-weight: bold;	
	font-size: 1.7vw;
	color:#eb240a;
	margin-left: 20vw;
}
.bannername {
	margin-right: 5px;
	padding: 0.5px 15px 2px 0.5px;
	background:#eb240a;
	color: #ffffff; 
}
.banner3vid{
	font-size: 2vw; 
	font-style: italic;
	font-weight:bold;
}

.batchtag{
	background: #111111;
	padding: 4.5px 10px;
}

.enrollNow {
	margin-left: 40px;
	background: none;
	border: 2px solid black;
	border-radius: 11px;
	font-size: 1.5vw;
	padding: 0.4vw 1.5vw;
	box-sizing: border-box;
}
.enrollNow2 {
	margin-left: 40px;
	background: none;
	border: 2px solid black;
	border-radius: 11px;
	font-size: 1.5vw;
	padding: 0.4vw 1.5vw;
	box-sizing: border-box;
}
.enrollNow3 {
	margin-left: 40px;
	background: none;
	border: 2px solid black;
	border-radius: 11px;
	font-size: 1.5vw;
	padding: 0.4vw 1.5vw;
	box-sizing: border-box;
}

.enrollNow:hover {
	background: #0089e2;
	color: whitesmoke;
	border-color: transparent;
}
.enrollNow2:hover {
	background: #0089e2;
	color: whitesmoke;
	border-color: transparent;
}
.enrollNow3:hover {
	background: #eb240a;;
	color: whitesmoke;
	border-color: transparent;
}
*/
@media (max-width: 576px){
.top {
	overflow: hidden;
	background:#010a05;
	padding: 1vw;
}

.banner1date{
color : #010a05;
background: #eeebeb;
font-size: 2vw;
margin-left: 75vw;
border-radius: 0.4vw;
line-height: 1.5;
}

.heading1{
	padding: 0;
	margin-bottom: 2vw;
}

.bannerquote{
	color : #010a05;
	background: #eeebeb;
	padding: 0.07vw;
	font-weight: bold;
	font-size: 2vw;
	border-radius: 0.5vw;
	margin-right: 63vw;
	line-height:1;
}

.text1{
	color: #eeebeb;
	font-weight: bold;
	font-size: 4vw;
	margin-right: 42.5vw;
}

.text2{
	color: #eeebeb;
	font-weight: bold;
	font-size: 4vw;
	margin-right: 31vw;
}

.audience{
	color: #eeebeb;
	font-size: 2vw;
	margin-right: 50vw;
	line-height: 0;
}
.content1{
	float:left;
	margin-left: 7vw;
}

.list1{
	text-align: left;
	list-style-image: url('../../assets/bullet.png');
	color: #eeebeb;
	font-size: 2.5vw;
	display: inline-block;
	margin-right: 1vw;
}
.list2{
	text-align: left;
	list-style-image: url('../../assets/bullet.png');
	color: #eeebeb;
	font-size: 2.5vw;
	display: inline-block;
	margin-left: 0vw;
}
li{
	line-height: 2;
}

.topdown{
	margin-top: 0.5vw;
	float: left;
}
.text3{
	color: #eeebeb;
	font-size: 2vw;
	border-radius: 0.3vw;
	display: inline-block;
	margin-left: 40vw;
	margin-right: 3vw;
}

.GEC{
	height: 8vw;
	display: inline-block;
}

.institute
{
	margin-left: 4vw;
	vertical-align: middle;
	display: inline-block;
	width: 20vw;
}
.institute span
{
	line-height: 1;
	font-size: 2vw;
	float: left;
	color: #eeebeb;
}

.bottom {
	display: flex;
	overflow: hidden;
	position: relative;
	width:100%;
	background:#eeebeb;
	height: 8vw; 
}

.b1
{
	float:left;
	margin-left: 10vw;
	margin-right: 0vw;
	margin-top: 1vw;
	height: 5vw;
}
.b2
{
	float: left;
	margin-left: 3vw;
	margin-top: 1vw;
	height: 5vw;
}
.c1{
	margin-left: 26vw;
}
.c2{
	margin-left: 3vw;
}

.contact{
	font-size: 1.8vw;
	display: inline-block;
	margin-top: 3vw;
}
.contact img{
	height: 2vw;
	margin-right: 0.5vw;
}

}
</style>
