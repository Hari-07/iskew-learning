<template>
	<div id="navComponent">
		<b-navbar toggleable="lg" class="nav">
			<b-navbar-brand class="mr-auto" href="#">
				<img class="brand-logo" src="@/assets/iskew-white.png" alt="Logo">
			</b-navbar-brand>
			<b-navbar-toggle class="hambutton" target="nav-collapse"></b-navbar-toggle>
			<b-collapse id="nav-collapse" is-nav>
				<b-navbar-nav class="ml-auto align-items-center" pills>
					<b-nav-item to="/" class="navlink"> Home </b-nav-item>
					<b-nav-item v-scroll-to="'#events' " class="navlink"> Courses </b-nav-item>
					<b-nav-item href="https://www.onlinetest.iskew.in" class="loginlink"> Login </b-nav-item>
				</b-navbar-nav>
			</b-collapse>
		</b-navbar>
	</div>
</template>

<script>
export default {
	name: 'NavMenu',
}
</script>


<style scoped>

.brand-logo{
	width: 8vw;
	margin-left: 5vw;
}

.navbar-nav .navlink >>> a {
	color:#111111 ;
	width: 90px;
	margin: 0 10px;
	border-radius: 4px;
}

.navbar-nav .navlink:hover >>> a {
	color:#0089e2
}

.navbar-nav .loginlink >>> a {
	color:white;
	background: #111111;
	width: 90px;
	margin: 0 10px;
	border-radius: 4px;
}

.navbar-nav .loginlink:hover >>> a {
	background: #0089e2;
	color:white;
}

.navbar-nav .loginlink:active,:focus,:visited >>> a {
	color:white
}

.hambutton{
	font-size: 14px;
}

@media (max-width: 576px){
	.brand-logo{
		width: 14vw;
	}
}
</style>