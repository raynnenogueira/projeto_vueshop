<template>
  <HeaderMain></HeaderMain>
  <ProductsMain></ProductsMain>
  <FooterMain></FooterMain>
  <main>
    <router-view/>
  </main>
</template>

<script>
  import HeaderMain from './components/HeaderMain.vue';
  import ProductsMain from './components/ProductsMain.vue';
  import FooterMain from './components/FooterMain.vue';
  
  export default{
    components: {
      HeaderMain,
      ProductsMain,
      FooterMain
    }
  }
</script>

<style>
</style>
