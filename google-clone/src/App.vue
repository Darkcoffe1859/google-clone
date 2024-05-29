<template>
  <v-app>
    <Header />
    <v-main>
      <SearchBar />
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import Header from './components/Header.vue'
import SearchBar from './components/SearchBar.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',

  components: {
    Header,
    SearchBar,
    Footer,
  },
}
</script>

