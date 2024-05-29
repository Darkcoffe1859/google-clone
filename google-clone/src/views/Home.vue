<template>
  <v-container>
    <Header />
    <v-main>
      <SearchBar />
    </v-main>
    <Footer />
  </v-container>
</template>

<script>
import Header from '@/components/Header.vue';
import SearchBar from '@/components/SearchBar.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: 'Home',
  components: {
    Header,
    SearchBar,
    Footer
  }
}
</script>

<style>
.v-container {
  text-align: center;
  margin-top: 100px;
}
</style>

