<template>
	<div id="eventlistentry">
		<b-button block class="schedulebutton" v-b-toggle href="#collap">
			<div class="scheduledeets">
				<div class="scheduledate">{{ date }} </div>
				<div class="schedulemonth">{{ month }}</div>
			</div>
			<div class="eventdetails">
				<div class="eventtitle">{{ title }}</div>
				<div class="eventtrainer"><strong>Trainer</strong>: {{ trainer }}</div>
			</div>
			<div class="stateIcon">
				<b-icon-chevron-down></b-icon-chevron-down>
			</div>
		</b-button>
		<b-collapse id="collap">
			<b-card>
				Hello world!
			</b-card>
		</b-collapse>
	</div>
</template>

<script>
import { BIconChevronDown } from 'bootstrap-vue'


export default {
	name: 'EventListEntry',
	props: {
		index: String,
		date: String,
		month: String,
		title: String,
		trainer: String
	},
	components: {
		BIconChevronDown
	},
}
</script>

<style>

.schedulebutton{
	background: none;
	color:black;
	display: flex;
	border:none;
	border-bottom: 2px solid #202020;
	border-radius: 0;
}

.schedulebutton:hover,:active,:target,:visited,:focus {
	color:black;
	background: none;
}

.scheduledeets {
	display: flex;
	flex-direction: column;
}

.scheduledate {
	font-weight:bold;
	font-size: 3vw;
	line-height: 2.5vw;
}

.schedulemonth{
	color: #959595;
	font-size: 1.05vw;
}

.eventdetails{
	display: flex;
	flex-direction: column;
	flex-grow: 1;
	text-align: left;
	margin: 0 3%;
}

.eventtitle{
	font-weight:bold;
	font-size: 2.5vw;
	line-height: 2.5vw;
}

.eventtrainer{
	font-size: 1.15vw;
}

.stateIcon {
	display: flex;
	flex-direction: column;
	justify-content: center;
}
</style>