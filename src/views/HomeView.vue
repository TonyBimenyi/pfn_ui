<template>
 <div class="home_template">
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
