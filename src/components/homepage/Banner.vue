<template>
	<div id="banner">
		<div class="quoteBox">
			<h1 class="bannerquote">
				Adding Value to <br> your life <span style="color:#0089e2">since 2008</span>
			</h1>
			<b-button v-scroll-to="'#events' " variant="outline-secondary" class="enrollbutton" @click.prevent>
				Enroll Now		
			</b-button>
		</div>
		<div style="flex-grow:1"></div>
		<img class="bannerimage" src="@/assets/bannerPic.png">
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