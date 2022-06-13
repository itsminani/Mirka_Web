<!-- ! Create small contact card for the main contacts -->
<template>
  <div class="box">
    <section class="hero is-fullheight">
      <div class="hero-body">
        <div class="container has-text-centered">
          <div class="columns is-8 is-variable">
            <!-- Address details -->
            <div class="column is-two-thirds has-text-left">
              <h1 class="title is-1">Contact Us</h1>
              <p class="is-size-4">
                <b class="is-size-4"> OUR LOCATION AND CONTACTS: </b>
                <br />
                Town Center Building , 4th floor, (Near Kigali City Tower) P.O.
                Box 221 Kigali, Rwanda <br />
                Website:www.mirka.rw Email:
                <a href="mailto:info@mirka.rw"> info@mirka.rw </a><br />
                <br />
              </p>
              <b class="title-styled is-size-4"> OUR CONTACTS: </b>
              <br />
              <br />
              <p>
                Gregoire MINANI Tel (and WhatsApp): +250 788 308 521 email:
                gminani@mirka.rw Antoine Uwamungu Tel (and WhatsApp): 0788306977
                email: antoineuwamungu@gmail.com Aline Murangira Tel (and
                WhatsApp):+250 788 405 056; email: amurangira@mirka.rw
                Antoinette Mukankundiye Tel (and WhatsApp): +250 788 735 370
              </p>
              <div class="social-media">
                <a
                  href="mailto:info@mirka.rw"
                  class="button is-light is-large m-2"
                  ><i aria-hidden="true">📧</i></a
                >
                <a href="tel:07889308521" class="button is-light is-large m-2"
                  ><i aria-hidden="true">📞</i></a
                >
                <a href="#" class="button is-light is-large m-2"
                  ><i aria-hidden="true">🌐</i></a
                >
              </div>
            </div>
            <!-- Contact Form -->
            <div class="column is-one-third has-text-left">
              <div class="field">
                <label class="label">Name</label>
                <div class="control">
                  <input class="input is-medium" type="text" />
                </div>
              </div>
              <div class="field">
                <label class="label">Email</label>
                <div class="control">
                  <input class="input is-medium" type="text" />
                </div>
              </div>
              <div class="field">
                <label class="label">Message</label>
                <div class="control">
                  <textarea class="textarea is-medium"></textarea>
                </div>
              </div>
              <div class="control">
                <button
                  type="submit"
                  class="button is-link is-fullwidth has-text-weight-medium is-medium"
                >
                  Send Message
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      subject: "",
      email: "",
      message: "",
      name: "",
    };
  },
  methods: {
    submit() {},
  },
};
</script>
