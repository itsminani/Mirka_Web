<template>
  <div class="home">
    <ContactForm msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import ContactForm from '@/components/ContactForm.vue'

export default {
  name: 'Home',
  components: {
    ContactForm
  }
}
</script>
