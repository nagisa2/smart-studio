<template>
  <div class="navbar">
    <div class="nav-logo" @click="home">
      <img src="../assets/logo.svg" alt="Logo" class="logo" />
    </div>
    <div class="nav-link">
      <RouterLink to="/" class="links">Home</RouterLink>
      <RouterLink to="/about" class="links">About us</RouterLink>
      <RouterLink to="/service" class="links">Services</RouterLink>
      <RouterLink to="/project" class="links">projects</RouterLink>
      <RouterLink to="/news" class="links">News</RouterLink>
    </div>
  </div>
</template>
<script setup>
import { RouterLink } from "vue-router";
</script>
<script>
export default {
  data() {
    return {};
  },

  methods: {
    home() {
      this.$router.push("/");
    },
  },
};
</script>
<style>
@import "../style/NavBar.css";
</style>
