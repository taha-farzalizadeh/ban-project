<template>
  <div class="banners">
    <Card link="book"></Card>
    <Card link="cosmetic"></Card>
    <Card link="fashion"></Card>
    <Card link="digital"></Card>
  </div>
</template>

<script>
import Card from '../components/card.vue'
export default {
  name: 'IndexPage',
  components:{
    Card
  }
}
</script>