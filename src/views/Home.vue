<template>
  <div class="home">
    <Banner />
    <Info />
    <Stats />
    <Events />
  </div>
</template>

<script>
import Banner from '@/components/homepage/Banner.vue'
import Info from '@/components/homepage/Info.vue'
import Stats from '@/components/homepage/Stats.vue'
import Events from '@/components/homepage/Events.vue'

export default {
  name: 'Home',
  components:{
    Banner,
    Info,
    Stats,
    Events,
  }
}
</script>
