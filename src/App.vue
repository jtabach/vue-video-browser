<template>
  <SearchBar @termChange="onTermChange"></SearchBar>
</template>

<script>
import SearchBar from "./components/SearchBar";
const API_KEY = "AIzaSyB7mh38OG-N1N8120WHrqoNkvmTcsNBfys";

export default {
  name: "App",
  components: {
    SearchBar
  },
  methods: {
    onTermChange(searchTerm) {
      console.log(searchTerm);
    }
  }
};
</script>
