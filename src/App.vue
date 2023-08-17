<template>
  <div id="app">
    <HeaderView />
    <SpeakersView/>
    <FooterView/>
  </div>
</template>

<script>
import HeaderView from './components/HeaderView.vue'
import SpeakersView from './components/SpeakersView.vue'
//import HeroView from './components/HeroView.vue'
//import TestimonialsView from './components/TestimonialsView.vue'
import FooterView from './components/FooterView.vue'

export default {
  components: {
    HeaderView,
    SpeakersView,
    //HeroView,
    //TestimonialsView,
    FooterView
  }
}
</script>

