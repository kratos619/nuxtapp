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
.intro {
  height: 300px;
  position: relative;
  padding: 30px;
  box-sizing: border-box;
  background-position: center;
  background-size: cover;
}
.intro h1 {
  position: absolute;
  top: 10%;
  left: 5%;
  width: 90%;
  font-size: 1.5rem;
  color: black;
  background-color: rgb(211, 211, 211);
  padding: 10px;
  border-radius: 10px;
  box-shadow: 3px 3px 3px black;
  box-sizing: border-box;
  border: 1px solid black;
}
</style>
