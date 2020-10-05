<template>
	<div id="thanks">
	<div class="wrappertnq">
		<div class="mx-auto" style="margin:none;padding:none;line-height:1"><img src="../assets/tnq.png" class="tnqgraphic"></div>
		<div class="mx-auto tnqtextmain"><h2>Thank You!</h2></div>
		<div class="tnqtext"><h4>Warm Greetings from iSkew Learning - An Insight job guru enterprise. At the outset we would like to thank you for registering with us. You will receive a mail regarding your payment confirmation and credential for the test portal.</h4></div>
	</div>
	</div>
</template>

<script>
export default {
	name:'Thanks'
}
</script>

<style>
.tnqgraphic {
	height: 40vw;
	width: auto;
}

.tnqtextmain h2{
	font-weight: bold;
}

.tnqtext h4{
	margin-left: 25vw;
	width: 50vw;
	margin-bottom: 5%;
}

@media (max-width: 576px){
	.tnqgraphic{
		height: 70vw;
	}

	.tnqtext h4{
		margin-left: 5vw;
		width: 90vw;
		font-size: 10px;
		margin-bottom: 10vh;
	}
}

</style>