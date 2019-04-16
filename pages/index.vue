<template>
  <section class="container">
    <Header></Header>
    <nuxt-link to="users/1">Clsik me</nuxt-link>
  </section>
</template>

<script>
import Header from "~/components/Heade.vue";

export default {
  components: {
    Header
  }
};
</script>

<style>
</style>
