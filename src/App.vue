<script setup>
import { RouterLink, RouterView } from "vue-router";
// import HelloWorld from "@/components/HelloWorld.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <!-- <HelloWorld msg="You did it!" /> -->
      <nav>
        <RouterLink to="/">Start</RouterLink>
        <RouterLink to="/mail">Mail</RouterLink>
        <RouterLink to="/code">Code</RouterLink>
        <RouterLink to="/upload">Upload</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;700&display=swap');
@import "@/assets/base.css";
@import "@/assets/main.css";

</style>
