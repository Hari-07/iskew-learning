<template>
	<div id="eventlistentry" @click="toggled = !toggled">
		<div class="schedulebutton">
			<div class="scheduledeets">
				<div class="scheduledate">{{ date }} </div>
				<div class="schedulemonth">{{ month }}</div>
			</div>
			<div class="eventdetails">
				<div class="eventtitle">{{ title }}</div>
				<div class="eventsubtext">
					<div class="eventtrainer">Trainer<strong>: {{ trainer }}</strong></div>
					<div class="eventtiming">Timing<strong>:{{ time }} </strong></div>
				</div>
			</div>
			<div class="stateIcon" :class={open:toggled}>
				<b-icon-chevron-down></b-icon-chevron-down>
			</div>
		</div>
		<div class="schedulecontent" :class={open:toggled}>
			<div class="schedulecontentdescription">
				Smart work takes you a long way vs hard work. To be smartly working, time management is a critical factor, and the purpose of effective goal setting is to achieve what you want in life in a successful, focused and decisive manner by taking the right actions in a lesser time frame. 
				Hop along the amazing session with iSkew on Sunday 27th of September
			</div>
			<div class="schedulecontentregister">
				<a :href="formLink">
					<button class="schedulecontentbutton">
						Join now
					</button>
				</a>
			</div>
		</div>
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
		trainer: String,
		time: String,
		formLink: String
	},
	components: {
		BIconChevronDown
	},
	data(){
		return {
			toggled: true
		}
	}
}
</script>

<style>

#eventlistentry {
	border-bottom: 2px solid #202020;
}

.schedulebutton{
	color:black;
	display: flex;
	margin-bottom:10px;
}

.schedulebutton:hover {
	cursor:pointer;
}
.schedulebutton:focus,:active{
	outline: none;
	border:none;
}

.scheduledeets {
	display: flex;
	flex-direction: column;
}

.scheduledate {
	font-weight:bold;
	font-size: 3vw;
	line-height: 1;
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
	font-size: 2.5vw;
	line-height: 1.2;
}

.eventsubtext {
	display: flex;
	margin-top:13px;
}

.eventtrainer{
	font-size: 1.15vw;
}
.eventtiming {
	padding-left:15vw;
	font-size: 1.15vw;
}

.stateIcon {
	display: flex;
	flex-direction: column;
	justify-content: center;
	font-size: 1.6vw;
}
.stateIcon.open{
	transform: scaleY(-1);
}

.schedulecontent {
	font-size: 1vw;
	text-align: left;
	padding-left: 5.70vw;
	margin-top:20px;
	color:#4A4A4A;
	display: flex;
	flex-direction: column;
	margin-bottom:20px;
	display: none;
}
.schedulecontent.open{
	display: block;
}

.schedulecontentregister{
	text-align: right;
}

.schedulecontentbutton{
	padding: 0.6vw 2.4vw;
	background: #111111;
	color: white;
	border-radius: 8px;
	outline: none;
	border:none;
}

@media (max-width: 576px){
	.scheduledate {
		font-size: 7vw;
	}
	.schedulemonth{
		font-size: 3.2vw;
	}
	.eventtitle{
		font-size:5vw
	}
	.eventtrainer{
		font-size: 2.5vw;
	}
	.eventtiming {
		padding-left:2.1vw;
		font-size: 2.5vw;
	}
	.schedulecontent{
		font-size: 2.5vw;
		padding-left: 2vw;
	}
	.schedulecontentregister{
		text-align: center;
	}
	.schedulecontentbutton{
		width: 100%;
		padding:6px 0 ;
		border-radius: 11px;
		margin-top:10px;
	}
	.stateIcon{
		font-size: 3.2vw;
	}
}
</style>