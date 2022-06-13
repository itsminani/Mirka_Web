<!-- ! Separate the code into Components -->
<!-- ! Add global styles -->
<!-- ! use sass where possible -->
<template>
  <div>
    <div class="">
      <div>
        <section class="hero mainhero is-success is-fullheight has-background">
          <div class="hero-body container has-text-centered">
            <div class="b" style="border: solid, white, 1px">
              <h1
                class="title-styled"
                style="margin: 3rem auto; font-size: 3rem; margin-bottom: 10px"
              >
                Make the right decision and acquire our insurance expertise on
                your side with no extra-charges
              </h1>
              <h2 class="subtitle">Mirka Insurace</h2>
            </div>
          </div>
          <div>
            <a href="#Medical">
              <p
                class="HoverServices"
                style="margin-bottom: 100px; margin-top: 0px; font-size: 30px"
              >
                <b-icon icon="chevron-double-down"> </b-icon>Our
                Services
              </p>
            </a>
          </div>
          <div class="hero-foot">
            <nav class="tabs is-boxed is-fullwidth">
              <div class="container">
                <ul>
                  <li :class="medicalActive" @click="activate('Medical')">
                    <a href="#Medical">Medical</a>
                  </li>
                  <li :class="propertyActive" @click="activate('Property')">
                    <a href="#Property">Property</a>
                  </li>
                  <li :class="motorActive" @click="activate('Motor')">
                    <a href="#Motor">Motor</a>
                  </li>
                </ul>
              </div>
            </nav>
          </div>
        </section>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      medicalActive: "",
      propertyActive: "",
      motorActive: "",
    };
  },
  methods: {
    disactivateClass() {},
    activate(name) {
      if (name == "Motor") {
        this.motorActive = "is-active";
        this.propertyActive = "";
        this.medicalActive = "";
      } else if (name == "Property") {
        this.propertyActive = "is-active";
        this.motorActive = "";
        this.medicalActive = "";
      } else if (name == "Medical") {
        this.medicalActive = "is-active";
        this.motorActive = "";
        this.propertyActive = "";
      }
    },
  },
};
</script>

<style lang="scss">
div {
  background-color: var(--bly);
}
</style>

<style>
html {
  scroll-behavior: smooth;
  font-family: "Poppins", Lato, Tahoma, sans-serif;
  width: 100%;
  min-height: 100%;
}
/* Hero landing page */
@import url("https://fonts.googleapis.com/css?family=Lato|Poppins|Kaushan+Script");
.has-vertically-aligned-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.mainhero {
  background-image: url(https://picsum.photos/id/381/1920/1080);
  background: linear-gradient(rgba(31, 44, 108, 0.65), rgba(31, 44, 108, 0.65)),
    rgba(0, 0, 0, 0.55) url("https://picsum.photos/id/381/1920/1080") no-repeat;
  background-attachment: fixed;
  background-size: cover;
  color: white;
  box-shadow: inset 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23);
  font-family: "Poppins", sans-serif;
}


.HoverServices {
  animation-name: updown;
  animation-duration: 2s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
  text-decoration: underline;
  cursor: pointer;
  transition: ease-in-out 2.3s;
}


@keyframes updown {
  from {
    transform: translateY(200px);
    transform: scale(1.1);
  }
  to {
    transform: scale(1.2);
  }
}

.main-content .section-color.services {
  padding: 100px;
  background-color: #43485c;
  color: white;
}

.main-content .section-color.services .title,
.main-content .section-color.services .subtitle {
  color: white;
}

.main-content .section-color.services i {
  font-size: 3rem;
  padding: 20px;
}

/* process */

.title::before,
.title::after {
  content: "~";
}

* {
  box-sizing: border-box;
}

.hero .title-styled {
  font-family: "Kaushan Script", sans-serif;
  transform: rotate(-5deg);
  font-size: 5rem;
  margin: auto;
  /* color: whitesmoke; */
}

.hero .subtitle {
  padding: 5px;
  color: whitesmoke;
}
.card {
  transition: transform 0.2s;
}
.card:hover {
  transform: scale(1.02);
  box-shadow: 0.2px 0.5px 11px rgb(192, 192, 192);
}
</style>
