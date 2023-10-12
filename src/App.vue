<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
    <hr />
  </header>

  <RouterView />
</template>

<style lang="scss">
nav {
  a {
    display: inline-block;
    margin: 20px;
  }
}
</style>
