<template>
  <Header />
  <Portfolio />
  <About />
  <Footer />
</template>

<script>
import Header from '../components/Header.vue';
import Portfolio from '../components/Portfolio.vue';
import About from '../components/About.vue';
import Footer from '../components/Footer.vue';

export default {
  name: 'HomeView',
  components: { Header, Portfolio, About, Footer }
}
</script>
