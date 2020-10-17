<template>
  <div id="app">
    <navbar></navbar>
    <grid></grid>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Grid from '@/components/Grid.vue'
export default {
  name: 'app',
  // props: {},
  data: function(){
    return {}
  },
  // computed: {},
  methods: {
    // -- Metodos
  },
  components: {
    'navbar':Navbar,
    'grid':Grid,
  },
}
</script>

<style scoped>
  
</style>

<!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/> -->
