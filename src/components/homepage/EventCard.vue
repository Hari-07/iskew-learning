<template>
	<div id="card">
		<div id="card2">

		</div>
	</div>
</template>

<script>
export default {

}
</script>

<style>

#card {
	background: #FAFAFA;
	height: 25vw;
	border-radius: 11px;
	border: inset 1px solid #111111;
	box-sizing: border-box;
	box-shadow: -2px 2px 8px rgba(0, 0, 0, 0.25);
	background-image: url('../../assets/CardBG.svg');
	background-size: 50%;
	background-repeat: no-repeat;
	background-position: bottom right;
}
#card2{
	height: 100%;
	width: 100%;
	background-image: url('../../assets/CardBGFlip.svg');
	background-size: 50%;
	background-repeat: no-repeat;
	background-position: top left;
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

@media (max-width: 576px){
	#card {
		height: 70vw;
	}
}

</style>