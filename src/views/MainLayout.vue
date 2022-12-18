<template>
  <div id="app">
    <section class="hero is-info is-fullheight">
      <div class="hero-head"></div>
      <div
        data-aos="fade-right"
        class="mt-6"
      >
        <figure>
          <img src="@/assets/img/undraw_maintenance.svg" />
        </figure>
      </div>
      <div class="hero-body">
        <div class="container has-text-centered">
          
          <div class="column is-6 is-offset-3">
            
            <h1 class="title">
              Mirka Insurance's Website is currently under maintenance
            </h1>
            <h2 class="subtitle">
              Please come back a bit later and we should be up and running.
            </h2>
          </div>
        </div>
      </div>
    </section>
    <!-- <div>
      <NavBar />
    </div>

    <div class="">
      <transition
        mode="out-in"
        enter-active-class="animate__animated animate__fadeIn"
        leave-active-class="animate__animated animate__fadeOut"
      >
        <router-view />
      </transition>
    </div> -->
  </div>
</template>

<script>
import NavBar from "../components/NavBar.vue";
export default {
  data() {
    return {};
  },
  components: {
    NavBar,
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
