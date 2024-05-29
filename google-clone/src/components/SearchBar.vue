<template>
  <v-container>
    <v-row justify="center">
      <v-col cols="12" md="6">
        <v-text-field
          v-model="searchQuery"
          append-icon="mdi-magnify"
          label="Search Google"
          single-line
          hide-details
        ></v-text-field>
        <v-btn @click="search">Search</v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'SearchBar',
  data() {
    return {
      searchQuery: ''
    };
  },
  methods: {
    search() {
      console.log(this.searchQuery);
      // Implement search functionality here
    }
  }
}
</script>

<style scoped>
.v-btn {
  margin-top: 10px;
}
</style>

