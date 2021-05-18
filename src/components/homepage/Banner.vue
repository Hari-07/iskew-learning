<template>
	<div id="banner">
		<div class="quoteBox">
			<h1 class="bannerquote">
				Adding Value to <br> your life <span style="color:#0089e2">since 2008</span>
			</h1>
			<img class="insight-logo" src="@/assets/insight_logo.png" alt="">
		</div>
		<div style="flex-grow:1"></div>
		<div>
			<div class="title-box">
				<span class="title-name">Renjit Ravi Keshav</span><br>
				<span class="title-role">Leadership Trainer & Career Coach</span>
			</div>
			<img class="bannerimage" src="@/assets/bannerPic.png">
		</div>
	</div>
</template>

<script>
export default {
	name:'Banner'
}
</script>

<style>
#banner {
	display: flex;
	position: relative;
	background-image: url('../../assets/GreyMatt.jpg');
	background-repeat: repeat;
	background-origin: border-box;
	background-size: cover;
}
.title-box{
	position: absolute;
	text-align: right;
	width: 13%;
	top: 70%;
	left: 58%;
	font-size: 1vw;
}
.title-name{
	color: #0089e2;
	font-weight: bold;
	border-bottom: 2px solid #0089e2;
}
.insight-logo{
	height: auto;
	width: 25%;
}
.bannerimage {
	height: 35vw;
	float: right;
	padding-right: 5vw;
}
.quoteBox{
	text-align: left;
	/* min-width: 550px; */
	margin-top:10vw ;
	margin-left: 10%;
}
.bannerquote {
	font-weight: bold;
	color: #111111;
	font-size: 4vw;
}
.enrollbutton {
	border-color: #111111;
	color: #111111;
	font-size: 1.2vw;
	margin-top: 15px;
	padding: 10px 30px;
	border-radius: 11px;
}
.enrollbutton:hover {
	background: #0089e2;
	border-color: #0089e2;
}
.enrollbutton:focus,:active {
	outline: none;
	box-shadow: none;
}
@media (max-width: 576px){
	
	#banner {
		flex-direction: column;
		align-items: center;
	}
	.title-box{
		top: 50%;
		left: 10%;
		font-size: 2vw;
		width: 20%;
	}
	.bannerimage {
		height: 70vw;
		width: auto;
	}
	.quoteBox{
	/* text-align: ; */
		margin-top:12vw;
		text-align: center;
		margin-left: 0;
		margin-bottom: 30px;
	}
	.bannerquote{
		font-size: 8vw;
	}
	.enrollbutton{
		font-size: 4vw;
	}
}
</style>