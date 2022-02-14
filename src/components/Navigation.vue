<template>
  <div class="navigation">
    <ul class="navlist"></ul>
      <li class="logo nav-item"><router-link to="/">ValorantSkinz</router-link></li>
      <li class="nav-item"><router-link to="/shop">Shop</router-link></li>
      <li class="nav-item"><router-link to="/about">About</router-link></li>
      <li class="nav-item"><router-link to="/help">Help</router-link></li>
  </div>
</template>

<script>
export default {
  name: 'Navigation',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  @import 'Navigation.css';
  @import '../vars.css';
</style>
