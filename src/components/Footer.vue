<template>
	<div id="footerarea">
		<div class="sociallinks">
			<a href="https://www.linkedin.com/company/i-skew/mycompany/"><dile-social-icon class="socialicon" icon="linkedin"></dile-social-icon></a>
			<a href="https://www.instagram.com/i_skew/"><dile-social-icon class="socialicon" icon="instagram"></dile-social-icon></a>
			<a href="https://www.instagram.com/i_skew/"><dile-social-icon class="socialicon" icon="youtube"></dile-social-icon></a>
		</div>
		<div class="brandfooter">
			<img class="brandfooterlogo" src="@/assets/iskew-black.png" alt="Logo">
		</div>
		<div class="hrstyle"></div>
		<div class="footercontactinfo">
			<div>
				iskewlearning@gmail.com
			</div>
			<!-- <div>
				
			</div> -->
		</div>
	</div>
</template>

<script>
import 'social-icon/dile-social-icon.js'

export default {
	name:'Footer'
}
</script>

<style>
#footerarea{
	background: #111111;
	display: flex;
	flex-direction: column;
	padding-top: 30px;
}

.sociallinks {
	text-align: center;
	display: flex;
	justify-content: center;
}

.socialicon {
	margin: 10px;
	--dile-social-icon-color:white;
	--dile-social-icon-size:2vw;
	color:white;
}

.brandfooterlogo{
	width: 100px;
	margin-top:20px
}

.hrstyle{
  margin: 25px 30px;
	border:none;
	height:2px;
	background: #4A4A4A;
}
.footercontactinfo {
	color:white;
	margin:0 30px 2.5vw 30px;
	display:flex;
	font-size: 1.3vw;
	justify-content: center;
}

@media (max-width: 576px) {
	.footercontactinfo{
		margin: 0 5vw 20px 5vw;
		font-size: 3.5vw;
	}

	.socialicon {
		margin: 10px;
		--dile-social-icon-color:white;
		--dile-social-icon-size:8vw;
		color:white;
	}
}

</style>