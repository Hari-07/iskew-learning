<template>
	<div id="card">
		<div id="card2">
			<div class="graphic" :class="programID">
			</div>
			<div class="programtitle">
				<span class="programhl">{{ programDetails }}</span> <br>
				Test Series
			</div>
			<div class="enrollbuttoncard">
				<a :href="formLink">
					<button class="cardbutton">
						Buy Now
					</button>
				</a>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name:'EventCard',
	props:{
		programID:String,
		programDetails:String,
		formLink:String
	}
}
</script>

<style>

#card {
	background: #FAFAFA;
	height: 25vw;
	border-radius: 11px;
	box-sizing: border-box;
	box-shadow: -2px 2px 8px rgba(0, 0, 0, 0.25);
	background-image: url('../../assets/CardBG.svg');
	background-size: 50%;
	background-repeat: no-repeat;
	background-position: bottom right;
}
#card:hover {
	transform: scale(1.02);
	transition-duration: 300ms;
}
#card2{
	height: 100%;
	width: 100%;
	background-image: url('../../assets/CardBGFlip.svg');
	background-size: 50%;
	background-repeat: no-repeat;
	background-position: top left;
	padding-top:9%;
}
.cardImage{
	height: 65%;
}
.cardTitle{
	height: 35%;
	background: white;
	border-radius: 0 0 11px 11px;
	box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.1);
}
.graphic{
	height:46%;
	margin-left: 56%;
}

.graphic.apt{
	background-image: url('../../assets/Aptitude.svg');
	background-size: 140% 100%;
}
.graphic.tech{
	background-image: url('../../assets/Coding.svg');
	background-size: 140% 100%;
}
.graphic.aptech{
	background-image: url('../../assets/COMBO.svg');
	background-size: 140% 100%;
}

.programtitle{
	text-align: left;
	margin-left: 15px;
	font-size: 1.8vw;
	line-height: 1.2;
	font-weight: bold;
}

.programhl{
	color:#0089E2;
}

.enrollbuttoncard{
	text-align: left;
	margin-left: 15px;
	padding-top: 16%;
}
.cardbutton{
	background:#FAFAFA;
	border: inset 1.5px solid black;
	border-radius: 11px;
	padding: 7px 22px;
	font-size:1.3vw;
}
.cardbutton:hover {
	background: #0089E2;
	color: white;
}
.cardbutton:focus {
	outline: none;
}

@media (max-width: 576px){
	#card {
		height: 70vw;
	}

	.programtitle{
		font-size:5vw
	}
	.enrollbuttoncard{
		padding-top:12%;
	}
	.cardbutton{
		font-size: 4vw;
	}
}

</style>