<template>
	<div class="footerarea">
		<p class="footertext">Contact us on <span class="footerhl">+91 90209 37077</span> or via Email at <a href="mailto:iskewlearning@gmail.com" class="footerhl">iskewlearning@gmail.com</a></p>
		<span class="footersociallink">
			<a href="https://www.linkedin.com/company/i-skew/mycompany/"><dile-social-icon class="socialicon" icon="linkedin"></dile-social-icon></a>
			<a href="https://www.instagram.com/i_skew/"><dile-social-icon class="socialicon" icon="instagram"></dile-social-icon></a>
		</span>
	</div>
</template>

<script>
import 'social-icon/dile-social-icon.js'

export default {
	name:'Footer'
}
</script>

<style>

.footerarea{
	border-top:1px solid grey;
	padding-top: 25px;
	margin-bottom: 40px;
	display: flex;
	flex-direction: column;
}

.footertext{
	font-size: 1.5vw;
}

.footerhl{
	color: #0089E2;
	font-weight:bold;
}

.footersociallink {
	justify-content: center;
	display: flex;
	--dile-social-icon-color: #111111;
}

.socialicon{
	padding:10px;
}

@media (max-width: 576px) {
	.footertext{
		font-size: 2.8vw;
	}
}
</style>