<template>
	<div id="events">
		<div class= "eventheader">
			iSkew Learning Programmes
			<div class="eventheadersubtext">These test series can be accessed via our webportal. Difficulty level of each question varies according to how you perform. Enjoy the test series.</div>
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
		<!-- <div id="#listofevents" class="eventlist">
			<div class="eventlisttitle">
				iSkew TCS Packages
			</div>	
			<div class="eventlistitems">
				<EventListEntry date=21 month="OCT" title="TCS NQT Aptitude Training Rs. 99" trainer="Duration: 3 Hours" time="Daily 7 PM - 8 PM" formLink="https://forms.gle/7PTnDbiH5UPnrwQm9" description="You should practice everyday to boost your confidence before TCS NQT Exam. Attend our sessions to improve your chance of clearing the exam." />
				<EventListEntry date=19 month="OCT" title="TCS NQT Mock Drill - Rs. 99" trainer="3 TCS NQT Full Length Papers" time="Video Solutions Included" formLink="https://rzp.io/l/mockdrill" description = "Attempt our TCS NQT Mock Drill tests and make yourself TCS NQT ready." />
				<EventListEntry date=19 month="OCT" title="TCS NQT Technical Training on C Programming - Rs. 299" trainer="Duration: 6 Hours" time="Daily 6 PM - 8 PM" formLink="https://forms.gle/dyYPskeoP8Hidu1i6" description="Core IT Jobs are all about the fundamentals. Join us to obtain a strong fundamental base and pave your way to a succesfull career" />
				<EventListEntry date=02 month="OCT" title="TCS NQT Test Series - Rs. 99" trainer="10 Quantitative Papers" time="5 Verbal Papers" formLink="https://forms.gle/SU87s2vx2r14JLWVA" description="You should practice everyday to boost your confidence before TCS NQT Exam. A complimentary E-Book on Personal Interview and Group discussion will be provided as well" />
			</div>
		</div> -->
	</div>
</template>

<script>
import EventCard from '@/components/homepage/EventCard.vue'
// import EventListEntry from '@/components/homepage/EventListItems.vue'

export default {
	name: 'Events',
	components:{
		EventCard,
		// EventListEntry
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
	font-size: 3vw;
	font-weight: bold;
	line-height: 1.6;
}
.eventheadersubtext{
	font-size: 1vw;
	font-weight: 400;

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
	border-radius: 11px;
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

	.eventheadersubtext{
		font-size: 3.4vw;
		text-align: justify;
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