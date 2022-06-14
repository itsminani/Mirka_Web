<template>
  <div class="home">
    <MainPage />
    <services/>
    <serviceContents/>
    <ContactForm msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src

import MainPage from "../components/MainPage.vue";
import ContactForm from '@/components/ContactForm.vue'
import Services from '../components/Services.vue';
import ServiceContents from '../components/ServiceContents.vue';




export default {
  name: 'Home',
  components: {
    ContactForm,
    MainPage,
    Services,
    ServiceContents
  }
}
</script>
