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
								iSkew started off as an online extension of the parent concept - Insight Job Guru, founded in 2008, which is a consortium of experts from the Training Industry, with over 10 years of proven experience in the fields of Soft Skills Development & Campus Recruitment Training. The consortium focuses on providing training services to Engineering, Arts & MBA colleges. We deliver comprehensive training programmes that address a wide range of requirements and bridge the gap between area of improvement and employability skills. 
								Through it’s online platform – iSkew Learning, we ensure to bring training programmes available to all on par with quality and content.
							</div>
						</div>
					</b-col>
				</b-row>
			</b-container>
		</div>
		<div class="mobileview">
			<div class="infocontainer">
				<div class="imagesizer">
					<img class="infoimage" src="@/assets/RK-2.jpg" alt="portrait photo">
				</div>
				<div class="infomember about content">
					<div class="contentheading">
						About iSkew
					</div>
					<div class="contenttext">
						iSkew started off as an online extension of the parent concept - Insight Job Guru, founded in 2008, which is a consortium of experts from the Training Industry, with over 10 years of proven experience in the fields of Soft Skills Development & Campus Recruitment Training. The consortium focuses on providing training services to Engineering, Arts & MBA colleges. We deliver comprehensive training programmes that address a wide range of requirements and bridge the gap between area of improvement and employability skills. 
						Through it’s online platform – iSkew Learning, we ensure to bring training programmes available to all on par with quality and content.
					</div>
				</div>
			</div>
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

.imagesizer{
	display: flex;
	flex-direction: column;
	align-items: flex-start;
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
	padding: 8.4% 18%;
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
		width: 40vw;
		height: auto;
	}

	.infomember.about.content{
		display:flex;
		height: 100%;
		flex-direction: column;
		justify-content: center;
		color: whitesmoke;
		padding: 12vw 10vw 0 0;
	}

	.contentheading{
		font-size: 4.5vw;
	}
	.contenttext{
		font-size: 2vw;
	}
	.infocontainer{
		display: flex;
	}

}

</style>