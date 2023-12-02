<template>
    <div>
      <h2>Carrinho de Compras</h2>
      <ProductsView :cartItems="cartItems" />
      <p>Total: R$ {{ calculateTotal() }}</p>
    </div>
  </template>
  
  <script>
  import ProductsView from '@/components/ProductsView.vue';
  
  export default {
    components: {
      ProductsView,
    },
    data() {
      return {
        cartItems: [],  
      };
    },
    methods: {
      calculateTotal() {
        return 0;  
      },
    },
  };
  </script>
  