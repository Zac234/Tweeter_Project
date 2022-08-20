<template>
 
</template>

<script>
import tweeterMainVue from './components/tweeterMain.vue';
import tweeterHeadVue from './components/tweeterHead.vue';
import tweeterFootvue from './components.tweeterFoot.vue';
export default {
  name: 'App',
  components: {
    
    tweeterHeadVue,
    tweeterMainVue,
    tweeterFootvue
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
