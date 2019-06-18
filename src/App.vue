<template>
  <!-- when using a component in a template Vue.js expects the DOM element to be
  lowercased and dasherized. e.g. ProductList -> product-list -->
  <div class="welcome">Hello World !</div>
  <!-- use the <product-list> component here! -->
</template>

<script>
  // import product list component
  export default {
    name: 'App',
    components: {
      // add product list as a component
    }
  }
</script>