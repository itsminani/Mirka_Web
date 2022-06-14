<template>
  <div>
    <MainLayout />
  </div>
</template>

<script>
import MainLayout from "./views/MainLayout.vue";
// eslint-disable-next-line no-undef
AOS.init({
  once: false,
  mirror: true,
  duration: 600,
});
export default {
  data() {
    return {};
  },

  components: {
    MainLayout,
  },
};
</script>


<style>
:root{
  --primary : red;
}

/* Helper Styles */
.is-primary{
  background-color: var(--primary);
}
</style>