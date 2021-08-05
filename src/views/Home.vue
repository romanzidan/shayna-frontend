<template>
  <div class="home">
    <Header/>
    <Hero/>
    <Product/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import Product from '@/components/Product.vue';

export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    Product
  }
}
</script>
