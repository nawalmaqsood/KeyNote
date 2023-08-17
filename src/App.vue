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
import FooterView from './components/FooterView.vue'

export default {
  components: {
    HeaderView,
    SpeakersView,
    FooterView
  }
}
</script>

