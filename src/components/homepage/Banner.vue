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

.banner1 {
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

.bannerbranding {
	color: #0089e2;
	font-size: 2vw;
	font-style: italic;
	line-height: 1;
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

.enrollNow:hover {
	background: #0089e2;
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

	.bannerbranding{
		font-size:4vw;
	}

	.bannerquote{
		font-size: 8vw;
	}
	.bannerquote2{
		font-size: 8vw;
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
}

</style>