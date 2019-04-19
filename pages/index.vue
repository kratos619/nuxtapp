<template>
  <div class="home-page">
    <section class="intro">
      <h1>Get the Letest Tech News</h1>
    </section>
    <section>
      <PostPriview
        id="1"
        thumbnail="https://picsum.photos/200/300/?random"
        title="this is title"
        perviewText="this is preview text"
      ></PostPriview>
    </section>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import PostPriview from "@/components/Posts/PostPreview";
export default {
  components: {
    Logo,
    PostPriview
  }
};
</script>

<style scoped>
</style>
