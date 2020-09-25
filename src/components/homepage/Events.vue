<template>
	<div id="events">
		<div class= "eventheader">
			iSkew Learning Programmes
		</div>
		<div class="eventcards">
			<b-container>
				<b-row>
					<b-col class="eventcard" sm="4"><EventCard formLink="https://forms.gle/m1kvkS9DNqs286JB8" programID="apt" programDetails="12 Aptitude"/></b-col>
					<b-col class="eventcard" sm="4"><EventCard formLink="https://forms.gle/pkYCodCL2jDbwxeN8" programID="tech" programDetails="3 Technical"/></b-col>
					<b-col class="eventcard" sm="4"><EventCard formLink="https://forms.gle/4SgqxJHJE5157tdQ6" programID="aptech" programDetails="15 Paper Combo"/></b-col>
				</b-row>
			</b-container>
		</div>
		<div class="eventlist">
			<div class="eventlisttitle">
				iSkew Event Schedule
			</div>	
			<div class="eventlistitems">
				<EventListEntry index=0 date=27 month="SEP" title="Time Management and Effective Goal Setting" trainer="Renjit Keshav" time="05:00 PM to 06:00 PM" formLink="https://forms.gle/tUarmAbB9h7Y6SDo7"/>
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
	border: 0.2px solid rgba(0, 0, 0, 0.2);
	padding: 1vw 3vw;
	border-radius: 6px;
	box-shadow: 4px 4px 20px 2px rgba(0, 0, 0, 0.05);
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