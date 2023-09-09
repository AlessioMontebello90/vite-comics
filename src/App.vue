<script>
import AppContent from "./components/AppContent.vue";
import AppFooter from "./components/AppFooter.vue";
import AppHeader from "./components/AppHeader.vue";
export default {
  components: { AppHeader, AppContent, AppFooter },
};
</script>

<template>
  <app-header />
  <main>
    <app-content />
  </main>
  <app-footer />
</template>

<style lang="scss">
@use "./assets/styles/general.scss";
</style>
