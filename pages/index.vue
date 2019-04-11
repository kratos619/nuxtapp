<template>
  <section class="container">
    <nuxt-link to="users/1">Clsik me</nuxt-link>
  </section>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  },
  layout: "Header"
};
</script>

<style>
</style>
