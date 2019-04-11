<template>
  <div>
    <h1>id is {{$route.params.id}}</h1>
  </div>
</template>

<script>
export default {
  validate(data) {
    console.log(data);
    return true;
  },
  layout: "Header"
};
</script>

<style>
</style>
