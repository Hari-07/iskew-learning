<template>
	<div class="bluestrip">
		<div class="stat">
			<div class="statvalue">12</div>
			<div class="stattag">Years of experience</div>
		</div>
		<div class="stat">
			<div class="statvalue">250,000</div>
			<div class="stattag">Students</div>
		</div>
		<div class="stat">
			<div class="statvalue">65</div>
			<div class="stattag">Colleges</div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'Stats'
}
</script>

<style>
.bluestrip{
	background: #0089E2;
	display: flex;
}

.stat{
	width: 100%;
	padding: 30px 0;
}

.statvalue{
	font-weight: bold;
	color: white;
	font-size: 3vw;
}

.stattag{
	color: #111111;
	font-weight: bold;
	font-size: 1.5vw;
}

@media (max-width: 576px){
	.stat{
		padding:10px 0;
	}

	.statvalue{
		font-size: 5.5vw;
	}
	.stattag{
		font-size: 2.5vw;
	}

}
</style>