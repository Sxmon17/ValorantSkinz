<template>
  <div class="home">
    <Navigation></Navigation>
  </div>
</template>

<script>
import Navigation from '../components/Navigation.vue'
export default {
  name: 'Home',
  components: {
    Navigation
  }
}
</script>
<style scoped>
  @import '../style.css';
  @import '../vars.css';
</style>
