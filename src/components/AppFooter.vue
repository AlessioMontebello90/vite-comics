<script>
export default {};
</script>

<template>
  <footer>
    <div class="options"></div>
    <div class="contacts"></div>
    <div class="socials"></div>
  </footer>
</template>

<style lang="scss" scoped>
@use "./../assets/styles/partials/variables.scss" as *;
.options {
  background-color: blue;
  height: 8rem;
  display: flex;
}
.contacts {
  background-image: url("../assets/img/footer-bg.jpg");
  height: 16rem;
}
.socials {
  height: 5rem;
  background-color: gray;
  margin-bottom: 2rem;
}
</style>
