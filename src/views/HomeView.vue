<template>
 <div class="home_container">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
 </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/footer.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style src="../assets/css/home.css" scoped>

</style>
