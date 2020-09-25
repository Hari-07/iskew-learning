<template>
	<div id="info">
		<div class="desktopview">
			<b-container fluid class="infocontainer">
				<b-row no-gutters>
					<b-col class="infomember im">
						<img class="infoimage" src="@/assets/RK-2.jpg" alt="portrait photo">
					</b-col>
					<b-col class="infomember about">
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
		<div class="mobileview">
			<b-container fluid class="infocontainer">
				<img class="infoimage" src="@/assets/RK-2.jpg" alt="portrait photo">
				<div class="infomember about content">
					<div class="contentheading">
						About iSkew
					</div>
					<div class="contenttext">
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit architecto voluptates cum dolores sapiente officiis sit vitae perspiciatis sed, est, expedita dolore. Odio commodi maiores dolore praesentium deserunt nostrum rem?
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit architecto voluptates cum dolores sapiente officiis sit vitae perspiciatis sed
					</div>
				</div>
			</b-container>
		</div>
	</div>
</template>

<script>
export default {
	name:'Info'
}
</script>

<style>

.mobileview {
	display: none;
}

.infoimage{
	height: auto;
	width: 22.3vw;
}

.container-fluid.infocontainer{
	padding:0;
}

.infomember.about{
	display: grid;
	place-items: center;
	overflow: hidden;
}

.infomember.im {
	background: #121212;
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

@media (max-width: 576px){

	.desktopview{
		display: none;
	}

	.mobileview{
		display: block;
	}

	.infocontainer{
		background: #121212;
	}
	.infoimage{
		width: 45vw;
	}

	.infomember.about.content{
		display:flex;
		height: 100%;
		flex-direction: column;
		justify-content: center;
		color: whitesmoke;
		padding: 16vw 10vw 0 0;
	}

	.contentheading{
		font-size: 4.5vw;
	}
	.contenttext{
		font-size: 2.5vw;
	}
	.infocontainer{
		display: flex;
	}

}

</style>