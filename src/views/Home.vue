<template>
  <div class="home">
    <Header/>
    <Hero/>
    <Product/>
    <Insta/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue';
import Hero from '@/components/Hero.vue';
import Product from '@/components/Product.vue';
import Insta from '@/components/Insta.vue';

export default {
  name: 'Home',
  components: {
    Header,
    Hero,
    Product,
    Insta
  }
}
</script>
