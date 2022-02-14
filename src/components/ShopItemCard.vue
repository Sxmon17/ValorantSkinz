<template>
  <div class="ShopItemCard">
    <div class="card-container">
      <h1>{{name}}</h1>
      <img src="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'ShopItemCard',
  props: {
    name: String,
    img: URL
  }
}
</script>
<style scoped>
  @import 'ShopItemCard.css';
  @import '../vars.css';
</style>
