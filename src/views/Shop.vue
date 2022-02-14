<template>
  <div class="shop">
    <Navigation></Navigation>
    <div id="shop-content-container">
      <ShopItemCard name="Vandal" img="../../assets/logo.png"></ShopItemCard> 
      <ShopItemCard name="Phantom"></ShopItemCard>
      <ShopItemCard></ShopItemCard> 
      <ShopItemCard></ShopItemCard> 
      <ShopItemCard></ShopItemCard> 
      <ShopItemCard></ShopItemCard>
      <ShopItemCard></ShopItemCard> 
      <ShopItemCard></ShopItemCard> 
      <ShopItemCard></ShopItemCard> 
      <ShopItemCard></ShopItemCard> 
      <ShopItemCard></ShopItemCard> 
      <ShopItemCard></ShopItemCard> 
      <li v-for="weapon in weapons" :key="weapon.id">
        {{ weapon.weapon }}
      </li>
    </div>
  </div>
</template>

<script>
import Navigation from '../components/Navigation.vue'
import ShopItemCard from '../components/ShopItemCard.vue'
export default {
  name: 'Shop',
  components: {
    Navigation,
    ShopItemCard
  },
  weapons: [
    {weapon: 'Vandal', id: 1},
    {weapon: 'Phantom', id: 2},
    {weapon: 'Guardian', id: 3},
    {weapon: 'Ares', id: 4},
    {weapon: 'Judge', id: 5},
    {weapon: 'Spectre', id: 6},
  ]
}
</script>
<style scoped>
  @import '../style.css';
  @import '../vars.css';
</style>
