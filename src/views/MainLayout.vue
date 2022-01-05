<template>
  <div id="app">
    <NavBar />
    <MainPage />
    <div class="">
      <transition
        mode="out-in"
        enter-active-class="animate__animated animate__fadeIn"
        leave-active-class="animate__animated animate__fadeOut"
      >
        <router-view />
      </transition>    </div>
  </div>
</template>
<script>
import NavBar from "../components/NavBar.vue";
import MainPage from "../components/MainPage.vue";
export default {
  data() {
    return {};
  },
  components: {
    NavBar,
    MainPage
  },
};
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
