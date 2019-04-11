<template>
  <div>
    <h1>Uses</h1>
    <input type="text" v-model="userId">
    <button v-on:click="onclickGo()">Click and go</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      userId: ""
    };
  },
  methods: {
    onclickGo() {
      this.$router.push(`users/${this.userId}`);
    }
  },
  layout: "Header"
};
</script>

<style>
</style>
