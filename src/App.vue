<template>
  <div id="layout">
    <Home />
    <About />
    <Benefits />
    <Developers />
    <Games />
    <Teams />
    <Feedback />
  </div>
</template>


<script>

import Home from '@/views/Home.vue'
import About from '@/views/About.vue'
import Benefits from '@/views/Benefits.vue'
import Developers from '@/views/Developers.vue'
import Games from '@/views/Games.vue'
import Teams from '@/views/Teams.vue'
import Feedback from '@/views/Feedback.vue'

export default {
  name: 'App',
  components: {
     Home, About, Benefits, Developers, Games, Teams, Feedback
  },

}
</script>

<style>
@import url("assets/libs/bootstrap/css/bootstrap.css");
@import url("assets/css/style.css");
</style>
