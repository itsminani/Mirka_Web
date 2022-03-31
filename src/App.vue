<template>
  <div>
      <MainLayout />
  </div>
  </template>

<script>
AOS.init({
  once: false,
  mirror: true,
  duration: 600,
});
import MainLayout from "./views/MainLayout.vue";
export default {
  data() {
    return {};
  },

  components: {
    MainLayout,
  },
};
</script>
