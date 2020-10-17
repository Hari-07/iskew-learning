<template>
	<div id="banner">
		<div class="banner2">
			<div class="quoteBox2">
				<h1 class="bannerquote2">
					<div class="bannerbranding">iSkew Learning</div>
					TCS NQT <span style="color:#0089e2">Aptitude Training</span>
				</h1>
				<div class="bannersubquote2"><span class="batchtag">BATCH III</span> <a href="https://forms.gle/7PTnDbiH5UPnrwQm9"><button class="enrollNow2">Enroll Now </button></a></div>
			</div>
		</div>
		<div class="banner3">
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
		</div>
	</div>
</template>

<script>

export default {
	name:'Banner',
}
</script>

<style>
.banner3 img{
	width: 2vw;
	margin-right: 1vw;
}
.banner1 {
	color:#000000;
	display: flex;
	position: relative;
	height: 35vw;
	background-image: url('../../assets/whiteBG.jpg');
	background-repeat: repeat;
	background-origin: border-box;
	background-size: cover;
	overflow: hidden;
}

.banner2{
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

@media (max-width: 576px){
	
	.banner1 {
		flex-direction: column;
		align-items: center;
		height: 95vw;
	}
	.banner2 {
		flex-direction: column;
		align-items: center;
		height: 80vw;
	}
	.banner3 {
		flex-direction: column;
		align-items: center;
		height: 80vw;
	}

	.bannerimage {
		margin-left:0vw;
		margin-top:0vw;
		height: 35vw;
		width: auto;
	}

	.quoteBox{
	/* text-align: ; */
		margin-top:8vw;
		text-align: center;
		margin-left: 0;
		margin-bottom: 30px;
	}
	.quoteBox2{
	/* text-align: ; */
		margin-top:24vw;
		text-align: center;
		margin-left: 0;
		margin-bottom: 30px;
	}
	.subbanner3{
		height: 97vw;
		width: 87vw;
	}
	.quoteBox3{
		margin: 20px;
		text-align: center;

	}

	.bannerbranding{
		font-size:4vw;
	}
	.bannerbranding2{
		font-size:3.5vw;
	}

	.bannerquote{
		font-size: 8vw;
	}
	.bannerquote2{
		font-size: 8vw;
	}
	.bannerquote3{
		font-size: 7vw;
	}

	.bannersubquote{
		font-size: 3.6vw
	}
	.bannersubquote2{
		margin-left: 36vw;
		width: 27vw;
		font-size: 3.6vw;
		display: flex;
		flex-direction: column;
	}
	.bannersubquote3{
		margin-left: 20vw;
		width: 40vw;
		font-size: 3.6vw;
		display: flex;
		flex-direction: column;
	}

	.enrollNow {
		font-size: 3vw;
		padding: 0.8vw 3vw;
	}
	.enrollNow2{
		font-size: 3vw;
		padding: 0.8vw 3vw;
		margin-top: 3vw;
		margin-left: 0;
	}
	.enrollNow3{
		font-size: 3vw;
		padding: 0.8vw 3vw;
		margin-top: 3vw;
		margin-left: 0;
	}
	.banner3vid{
		font-size: 4vw;
	}
	.banner3 img{
		width: 4vw;
		margin-right: 1vw;
	}
}

</style>