<template>
	<div id="banner">
			<!-- <div class="quoteBox">
				<h1 class="bannerquote">
					Adding Value to <br> your life <span style="color:#0089e2">since 2008</span>
				</h1>
				<b-button v-scroll-to="'#events' " variant="outline-secondary" class="enrollbutton" @click.prevent>
					Enroll Now		
				</b-button>
			</div>
			<div style="flex-grow:1"></div>
			<img class="bannerimage" src="@/assets/bannerPic.png"> -->
			<div class="tcssidebar">
				<div class="element">
					<img class="elementimage" src="@/assets/5.png">
					<div class="elementtext">300+ TCS NQT Questions</div>
				</div>
				<div class="element">
					<img class="elementimage" src="@/assets/4.png">
					<div class="elementtext">12 Tests</div>
				</div>
				<div class="element">
					<img class="elementimage" src="@/assets/3.png">
					<div class="elementtext">Detailed Video Solutions</div>
				</div>
				<div class="element">
					<img class="elementimage" src="@/assets/2.png">
					<div class="elementtext">Expert Guidance</div>
				</div>
				<div class="element">
					<img class="elementimage" src="@/assets/1.png">
					<div class="elementtext">Live Zoom Training</div>
				</div>
			</div>
			<div class="quoteBox">
				<h1 class="bannerquote">
					<span style="color:white">TCS Aptitude Question <br> Paper Discussion <br> <span class="batch2">BATCH II</span></span>
				</h1>
				<div class="bannerbuttons">
					<a href="https://forms.gle/hyd895i85AsS1Vpp7">
						<button variant="outline-secondary" class="enrollbutton">
							Enroll Now		
						</button>
					</a>
					<b-button v-scroll-to="{ el: '#events', offset: 400 }" variant="outline-secondary" class="moreprogrammesbutton" @click.prevent>
						More Info		
					</b-button>
					<a href="https://drive.google.com/uc?export=download&id=1ZX5TJ1WeKzySAXviMmE7wHFi077vOVq1" target="_blank">
						<button class="tcsschedulebutton">Click Here for Full Schedule</button>
					</a>
				</div>
			</div>
			<div style="flex-grow:1"></div>
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
	background-image: url('../../assets/BannerBG.jpg');
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
	margin-top:8vw ;
	margin-left: 5vw;
}

.bannerquote {
	font-weight: bold;
	color: #111111;
	font-size: 4vw;
}

.batch2{
	font-weight: 300;
	color:grey;
	font-size: 3vw;
}

.bannerbuttons {
	margin-top: 15px;
}

.enrollbutton {
	border:2px solid white;
	color: white;
	background: none;
	font-size: 1.2vw;
	border-radius: 11px;
	padding: 0.5vw 30px;
	height:3vw;
}

.enrollbutton:hover {
	color:white;
	background: #111111;
}

.enrollbutton:focus,:active {
	outline: none;
	box-shadow: none;
}

.moreprogrammesbutton {
	border:2px solid white;
	color: white;
	background: none;

	font-size: 1.2vw;
	border-radius: 11px;
	padding: 0.45vw 30px;
	height:3vw;
	margin-left: 2vw;
}

.moreprogrammesbutton:hover {
	color:black;
	background: white;
}

.moreprogrammesbutton:focus,:active {
	outline:none;
	box-shadow: none;
}

.tcsschedulebutton {
	color: white;
	background: none;
	border:none;
	font-size: 1.2vw;
	border-radius: 11px;
	padding: 0.5vw 30px;
	height:3vw;
	margin-left: 0.5vw;
}

.tcsschedulebutton a:any-link{
	color:white;
}

.tcsschedulebutton:hover {
	color:white;
}

.tcssidebar{
	background: white;
	height: 100%;
	width: 8vw;
	border-radius: 0 77px 77px 0;
	box-shadow: 4px 2px 20px rgba(0, 0, 0, 0.2);
	display: flex;
	flex-direction: column;
	padding: 2vw 0.8vw 2vw 0.2vw;
}

.element{
	flex: 1;
}

.elementimage{
	width: auto;
	height: 3vw;
}

.elementtext{
	font-size:0.8vw;
	font-weight: bold;
}

@media (max-width: 576px){
	
	#banner {
		flex-direction: column;
		align-items: center;
		height: 90vw;
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

	.batch2{
		font-size: 6vw;
	}

	.enrollbutton{
		font-size: 4vw;
		padding: 0.5vw 20px;
		height:8vw;
	}

	.moreprogrammesbutton {
		font-size: 4vw;
		padding: 0.45vw 20px;
		height:8vw;
		margin-left: 2vw;
	}

	.tcsschedulebutton{
		font-size: 4vw;
		padding: 0.5vw 20px;
		height:8vw;
		margin-left: 0.5vw;
	}

	.tcssidebar{
		flex-direction: row;
		margin-top:5vw;
		border-radius: 11px;
		width: 70vw;
	}

	.elementimage{
		height: 6vw;
	}

	.elementtext{
		font-size: 1.7vw;
	}
}

</style>