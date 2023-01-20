
<template>
    <v-app id="inspire">
        <the-header @change-drawer="drawer = !drawer"></the-header>
        <shopping-cart :drawerProp="drawer"></shopping-cart>
        <product-overview></product-overview>
    </v-app>
  </template>
  
  <script>
import ProductOverview from './components/ProductOverview.vue';
import ShoppingCart from './components/ShoppingCart.vue';
import TheHeader from './components/TheHeader.vue';

    export default {
    data: () => ({ drawer: false }),
    components: { TheHeader, ShoppingCart, ProductOverview },
    methods: {

    }
}
  </script>