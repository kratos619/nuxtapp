<template>
  <section class="single-post-page">
    <article class="post">
      <h1 class="post-title">title</h1>
      <div class="post-details">
        <div class="post-detail">last update on XXx</div>
        <div class="post-detail">written by Name</div>
        <p>Content of the post</p>
      </div>
    </article>
    <section
      class="post-feedback"
    >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vitae, nesciunt?</section>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.single-post-page {
  padding: 30px;
  text-align: center;
  box-sizing: border-box;
}

.post {
  width: 100%;
}

@media (min-width: 768px) {
  .post {
    width: 600px;
    margin: auto;
  }
}

.post-title {
  margin: 0;
}

.post-details {
  padding: 10px;
  box-sizing: border-box;
  border-bottom: 3px solid #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

@media (min-width: 768px) {
  .post-details {
    flex-direction: row;
  }
}

.post-detail {
  color: rgb(88, 88, 88);
  margin: 0 10px;
}

.post-feedback a {
  color: red;
  text-decoration: none;
}

.post-feedback a:hover,
.post-feedback a:active {
  color: salmon;
}
</style>
