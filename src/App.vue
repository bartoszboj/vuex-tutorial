<template>
  <div id="app">
    <product-list-one></product-list-one>
    <product-list-two></product-list-two>
  </div>
</template>

<script>
import ProductListOne from '@/components/ProductListOne.vue'
import ProductListTwo from '@/components/ProductListTwo.vue'

export default {
  name: 'App',
  components: {
    ProductListOne,
    ProductListTwo
  },
  data () { 
    return{
      
    }
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

  body{
    font-family: 'Roboto', sans-serif;
  }
</style>
