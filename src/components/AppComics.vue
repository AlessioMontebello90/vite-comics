<script>
export default {
  props: {
    urlImg: String,
    series: String,
    price: String,
  },
};
</script>

<template>
  <div class="cards">
    <img :src="urlImg" :alt="series" />
    <div class="text-container">
      <h3>{{ series }}</h3>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
