<template>
	<div class="bluestrip">
		<b-container >
			<b-row>
				<b-col sm="4">
					<div class="stat">
						<div class="statvalue">12</div>
						<div class="stattag">Years of experience</div>
					</div>
				</b-col>
				<b-col sm="4">
					<div class="stat">
						<div class="statvalue">250,000</div>
						<div class="stattag">Students</div>
					</div>
				</b-col>
				<b-col sm="4">
					<div class="stat">
						<div class="statvalue">65</div>
						<div class="stattag">Colleges</div>
					</div>
				</b-col>
			</b-row>
		</b-container>
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
	padding: 90px 0;
}

.statvalue{
	font-weight: bold;
	color: white;
	font-size: 5vw;
	line-height: 1;
}

.stattag{
	color: #111111;
	font-size: 1.2vw;
}

@media (max-width: 576px){
	.stat{
		padding:20px 0;
	}

	.statvalue{
		font-size: 9vw;
	}
	.stattag{
		font-size: 3vw;
	}

}
</style>