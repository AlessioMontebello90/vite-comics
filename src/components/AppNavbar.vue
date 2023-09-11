<script>
export default {
  props: {
    title: String,
    link: String,
  },
};
</script>

<template>
  <div class="nav-container">
    <nav>
      <ul class="head_list">
        <li>
          <a href="#">{{ title }}</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<style lang="scss" scoped>
.nav-container {
  background-color: white;
  height: 6rem;
  nav {
    max-width: 1200px;
    margin: auto;
    height: 6rem;
    display: flex;
    align-items: center;
    justify-content: space-between;

    .head_list {
      list-style: none;
      display: flex;
      justify-content: flex-end;
      padding-inline: 1rem;
      font-size: 0.7rem;
      li {
        padding-inline: 1rem;
        a {
          color: black;
          text-decoration: none;
          font-size: 1rem;
        }
      }
    }
  }
}
</style>
