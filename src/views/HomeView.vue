<template>
  <div class="all_home">
    <div class="home_container">
      <div class="title">
        <h1>Loving God, Loving Other <br> and serving the world!</h1>
        <p>Experience God's love and grace in a welcoming community where faith grows, hope thrives, and everyone is cherished.</p>
        <div class="buttons">
          <div class="left_button">
            <button>Join In Person <i class="fas fa-heart"></i></button>
          </div>
          <div class="right_button">
            <button>Donate Now <i class="fas fa-heart"></i></button>
          </div>
        </div>
        <!-- Scroll Down Button -->
        <div class="scroll-down">
          <button @click="scrollToNextSection" aria-label="Scroll to next section">
            <i class="fas fa-down-long"></i>
          </button>
        </div>
      </div>
      <div class="description"></div>
    </div>
    <div class="marquee_container" id="next-section">
      <div class="marquee_wrapper">
        <h1 class="marquee_txt">
         <span> <img src="../assets/images/icon-sparkles.svg" alt=""> </span> Love your neighbor as yourself <span> <img src="../assets/images/icon-sparkles.svg" alt=""> </span>
        </h1>
        <h1 class="marquee_txt">
         <span> <img src="../assets/images/icon-sparkles.svg" alt=""> </span> Love your neighbor as yourself <span> <img src="../assets/images/icon-sparkles.svg" alt=""> </span>
        </h1>
        <h1 class="marquee_txt">
         <span> <img src="../assets/images/icon-sparkles.svg" alt=""> </span> Love your neighbor as yourself <span> <img src="../assets/images/icon-sparkles.svg" alt=""> </span>
        </h1>
        <h1 class="marquee_txt">
         <span> <img src="../assets/images/icon-sparkles.svg" alt=""> </span> Love your neighbor as yourself <span> <img src="../assets/images/icon-sparkles.svg" alt=""> </span>
        </h1>
        <h1 class="marquee_txt">
         <span> <img src="../assets/images/icon-sparkles.svg" alt=""> </span> Love your neighbor as yourself <span> <img src="../assets/images/icon-sparkles.svg" alt=""> </span>
        </h1>
        

      </div>
    </div>
    <about-us></about-us>
    <worship></worship>
  </div>
</template>

<script>
import aboutUs from '../components/about.vue';
import worship from '../components/worship.vue';
export default {
  components: {
    aboutUs,
    worship,
  },
  methods: {
    scrollToNextSection() {
      const nextSection = document.getElementById('next-section');
      if (nextSection) {
        nextSection.scrollIntoView({ behavior: 'smooth' });
      }
    }
  }
};
</script>
<style src="../assets/css/home.css" scoped>

</style>
