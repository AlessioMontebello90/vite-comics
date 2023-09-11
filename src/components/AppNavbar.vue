<script>
export default {
  props: {
    title: String,
    link: String,
  },
};
</script>

<template>
  <nav>
    <ul class="head_list">
      <li>
        <a href="#">{{ title }}</a>
      </li>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>
nav {
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
        &:hover {
          color: rgb(12, 119, 234);
        }
      }
    }
  }
}
</style>
