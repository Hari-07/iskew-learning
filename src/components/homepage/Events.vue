<template>
	<div id="events">
		<div class= "eventheader">
			iSkew Learning Programmes
		</div>
		<div class="eventcards">
			<b-container>
				<b-row>
					<b-col class="eventcard" sm="4"><EventCard /></b-col>
					<b-col class="eventcard" sm="4"><EventCard /></b-col>
					<b-col class="eventcard" sm="4"><EventCard /></b-col>
				</b-row>
			</b-container>
		</div>
		<div class="eventlist">
			<div class="eventlisttitle">
				iSkew Event Schedule
			</div>	
			<div class="eventlistitems">
				<EventListEntry index=0 date=27 month="SEP" title="Time Management and Effective Goal Setting" trainer="Renjit Keshav"/>
			</div>
		</div>
	</div>
</template>

<script>
import EventCard from '@/components/homepage/EventCard.vue'
import EventListEntry from '@/components/homepage/EventListItems.vue'

export default {
	name: 'Events',
	components:{
		EventCard,
		EventListEntry
	}
}
</script>

<style>
#events {
	width:100%;
	padding: 5% 10%;
}

.eventheader {
	text-align: left;
	width: 100%;
	font-size: 2.5vw;
	font-weight: bold;
}

.eventcard {
	margin-top: 20px;
}

.eventlisttitle {
	text-align: left;
	width: 100%;
	font-size: 2.5vw;
	font-weight: bold;
	margin-top:30px;
	margin-bottom: 10px;
}

.eventlistitems {
	border: 0.2px solid black;
	padding: 1vw 3vw;
	border-radius: 11px;
}

@media (max-width: 576px){
	#events {
		width:100%;
		padding: 5% 8%;
	}

	.eventheader {
		text-align: left;
		width: 100%;
		font-size: 5vw;
		font-weight: bold;
	}

	.eventlisttitle {
		text-align: left;
		width: 100%;
		font-size: 5vw;
		font-weight: bold;
		margin-top:20px;
		margin-bottom: 10px;
	}
}
</style>