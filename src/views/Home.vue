<template>
  <div class="home">
    <Banner />
    <Info />
    <Stats />
    <Events />
    <Footer />
  </div>
</template>

<script>
import Banner from '@/components/homepage/Banner.vue'
import Info from '@/components/homepage/Info.vue'
import Stats from '@/components/homepage/Stats.vue'
import Events from '@/components/homepage/Events.vue'
import Footer from '@/components/homepage/Footer.vue'

export default {
  name: 'Home',
  components:{
    Banner,
    Info,
    Stats,
    Events,
    Footer
  }
}
</script>
