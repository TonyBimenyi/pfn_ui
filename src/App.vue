<template>

   <nav-bar></nav-bar>

  <router-view/>
</template>

<script>
import navBar from './components/header.vue';
export default {
  name: 'App',
  components: {
    navBar
  },
  data() {
    return {
      // Data properties can be added here if needed
    };
  },
  methods: {
    // Methods can be added here if needed
  }
}
</script>

<style lang="scss">

</style>
