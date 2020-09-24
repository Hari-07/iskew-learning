<template>
	<div id="info">
		<b-container fluid class="infocontainer">
			<b-row no-gutters>
				<b-col sm="6" style="background:red" class="infomember">
					<img class="infoimage" src="@/assets/RK.png" alt="portrait photo">
				</b-col>
				<b-col sm="6" class="infomember about">
					<div class="content">
						<div class="contentheading">
							About iSkew
						</div>
						<div class="contenttext">
							Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit architecto voluptates cum dolores sapiente officiis sit vitae perspiciatis sed, est, expedita dolore. Odio commodi maiores dolore praesentium deserunt nostrum rem?
							Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit architecto voluptates cum dolores sapiente officiis sit vitae perspiciatis sed
						</div>
					</div>
				</b-col>
			</b-row>
		</b-container>
	</div>
</template>

<script>
export default {
	name:'Info'
}
</script>

<style>

	.infoimage{
		height: auto;
		width: 100%;
	}

	.container-fluid.infocontainer{
		padding:0;
	}

	.infomember.about{
		display: grid;
		place-items: center;
	}

	.content{
		height: 100%;
		padding: 20%;
	}

	.contentheading {
		font-size: 3vw;
		font-weight: 700;
		text-align: left;
	}

	.contenttext{
		text-align: justify;
		font-size: 1.3vw;
	}
</style>