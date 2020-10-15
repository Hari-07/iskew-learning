<template>
	<div id="banner">
			<div class="quoteBox">
				<h1 class="bannerquote">
					<span style="color:#0089e2">Fundamentals of C Programming & Data Structures</span>
				</h1>
				<div class="bannersubquote">Oct 19-21, 6 hours</div>
			</div>
			<img class="bannerimage" src="@/assets/gummy.png">
	</div>
</template>

<script>

export default {
	name:'Banner',
}
</script>

<style>

#banner {
	display: flex;
	position: relative;
	height: 35vw;
	background-image: url('../../assets/whiteBG.jpg');
	background-repeat: repeat;
	background-origin: border-box;
	background-size: cover;
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
	min-width: 35vw;
}

.bannerquote {
	font-weight: bold;
	color: #111111;
	font-size: 4vw;
}

.bannersubquote{
	font-weight: bold;
	font-size: 1.8vw;
	font-style: italic;
}

@media (max-width: 576px){
	
	#banner {
		flex-direction: column;
		align-items: center;
		height: 95vw;
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

	.bannerquote{
		font-size: 8vw;
	}

	.bannersubquote{
		font-size: 3.6vw
	}
}

</style>