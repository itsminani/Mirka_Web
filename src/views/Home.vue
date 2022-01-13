<template>
  <div class="home">
    <MainPage />
    <ContactForm msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>

// @ is an alias to /src


import MainPage from "../components/MainPage.vue";
import ContactForm from '@/components/ContactForm.vue'




export default {
  name: 'Home',
  components: {
    ContactForm,
    MainPage
  }
}
</script>
