<template>
	<div id="footerarea">
		<div class="sociallinks">
			<a href="https://www.linkedin.com/company/i-skew/mycompany/"><dile-social-icon class="socialicon" icon="linkedin"></dile-social-icon></a>
			<a href="https://www.instagram.com/i_skew/"><dile-social-icon class="socialicon" icon="instagram"></dile-social-icon></a>
			<a href="https://www.instagram.com/i_skew/"><dile-social-icon class="socialicon" icon="youtube"></dile-social-icon></a>
			<p class="socialicon">#iskewlearning</p>
		</div>
		<div class="brandfooter">
			<img class="brandfooterlogo" src="@/assets/iskew-black.png" alt="Logo">
		</div>
		<div class="hrstyle"></div>
		<div class="footercontactinfo">
			<div>
				iskewlearning@gmail.com
			</div>
			<div>
				+91 90209 37077
			</div>
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
	color:white;
}

.brandfooterlogo{
	width: 150px;
	margin-top:20px
}

.hrstyle{
  margin: 25px 75px;
	border:none;
	height:2px;
	background: #4A4A4A;
}
.footercontactinfo {
	color:white;
	margin:0 10vw 2.5vw 10vw;
	display:flex;
	justify-content: space-between;
}


</style>