<template>
  <div class="app-rc">
    <NavBar />
    <RouterView />
  </div>
</template>
<script setup>
import { RouterView } from "vue-router";
import NavBar from "./components/NavBar.vue";
</script>
<style>
@import "./style/global.css";
</style>
