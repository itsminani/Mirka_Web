<template>
  <div>
    <div class="">
      <div>

        <section class="hero mainhero is-success is-fullheight has-background">
          <!-- <img
            class="hero-background is-transparent"
            src="https://www.fillmurray.com/1920/1080"
            alt=""
          /> -->
          <div class="hero-body container has-text-centered">
            <div>
              
              <h1 class="title" style="font-size: 60px; margin-bottom: 10px">
                Leave the insurance to us
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
                <b-icon class="scroll" icon="chevron-double-down"> </b-icon>Our
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
      <div class="services" style="margin-top: 30px">
        <section class="hero is-fullheight">
          <div class="container">
            <div class="columns features">
              <div class="column is-4">
                <div class="card is-shady">
                  <div class="card-image">
                    <figure class="image is-4by3">
                      <img
                        src="https://source.unsplash.com/RWnpyGtY1aU"
                        alt="Placeholder image"
                        class="modal-button"
                        data-target="modal-image2"
                      />
                    </figure>
                  </div>

                  <div class="card-content">
                    <div class="content">
                      <h4>Medical Insurance</h4>
                      <p>
                        Purus semper eget duis at tellus at urna condimentum
                        mattis. Non blandit massa enim nec. Integer enim neque
                        volutpat ac tincidunt vitae semper quis. Accumsan tortor
                        posuere ac ut consequat semper viverra nam.
                      </p>
                      <span
                        class="button is-link modal-button"
                        data-target="modal-image2"
                        >Image modal</span
                      >
                    </div>
                  </div>
                </div>
              </div>
              <div class="column is-4">
                <div class="card is-shady">
                  <div class="card-image">
                    <figure class="image is-4by3">
                      <img
                        src="https://source.unsplash.com/6Ticnhs1AG0"
                        alt="Placeholder image"
                      />
                    </figure>
                  </div>
                  <div class="card-content">
                    <div class="content">
                      <h4>Property Insurance</h4>
                      <p>
                        Ut venenatis tellus in metus vulputate. Amet consectetur
                        adipiscing elit pellentesque. Sed arcu non odio euismod
                        lacinia at quis risus. Faucibus turpis in eu mi bibendum
                        neque egestas cmonsu songue. Phasellus vestibulum lorem
                        sed risus.
                      </p>
                      <span
                        class="button is-link modal-button"
                        data-target="modal-card"
                        >Modal Card</span
                      >
                    </div>
                  </div>
                </div>
              </div>
              <div class="column is-4 modal-button" data-target="modal-image">
                <div class="card is-shady">
                  <div class="card-image">
                    <figure class="image is-4by3">
                      <img
                        src="https://res.cloudinary.com/ameo/image/upload/v1568711475/pexels-photo-1302883_fjje0f.jpg"
                        alt="Placeholder image"
                      />
                    </figure>
                  </div>
                  <div class="card-content">
                    <div class="content">
                      <h4>Motor Insurance</h4>
                      <p>
                        Imperdiet dui accumsan sit amet nulla facilisi morbi.
                        Fusce ut placerat orci nulla pellentesque dignissim
                        enim. Libero id faucibus nisl tincidunt eget nullam.
                        Commodo viverra maecenas accumsan lacus vel facilisis.
                      </p>
                      <span
                        class="button is-link modal-button"
                        data-target="modal-image"
                        >Image modal</span
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
      </div>
      <div class="mainServices">
        <div id="Medical">
          <section class="hero is-white is-fullheight">
            <div class="hero-body">
              <div class="container">
                <div class="columns is-vcentered reverse-columns">
                  <div
                    class="column is-10-mobile is-offset-1-mobile is-10-tablet is-offset-1-tablet is-5-desktop is-offset-1-desktop is-5-widescreen is-offset-1-widescreen is-5-fullhd is-offset-1-fullhd"
                    data-aos="fade-down"
                  >
                    <h4 class="title titled is-1 mb-6">Medical</h4>
                    <h2
                      class="subtitled subtitle has-text-grey is-4 has-text-weight-normal is-family-sans-serif"
                    >
                      People deserve to discover the story of a human industry
                      that cares about its craft. PivoHub provides powerful and
                      simple software to create a digital ecosystem that
                      connects, organizes, and equips the craft beverage
                      industry. We will be the best-of-breed craft beverage
                      marketplace working with the world’s most notorious
                      artisans.
                    </h2>
                    <div class="buttons">
                      <b-button
                        class="button is-primary is-rounded"
                        to="/sell"
                        @click="showRegister = true"
                        size="is-large"
                        >Sell</b-button
                      >

                      <router-link to="/shop">
                        <b-button
                          class="button isrounded is-outlined is-rounded"
                          size="is-large"
                          >Buy</b-button
                        >
                      </router-link>
                    </div>
                  </div>
                  <div
                    data-aos="fade-right"
                    class="column is-10-mobile is-offset-1-mobile is-10-tablet is-offset-1-tablet is-4-desktop is-offset-1-desktop is-4-widescreen is-offset-1-widescreen is-4-fullhd is-offset-1-fullhd"
                  >
                    <figure>
                      <img src="@/assets/img/undraw_refreshing.svg" />
                    </figure>
                  </div>
                </div>
              </div>
            </div>
          </section>
        </div>
        <div id="Property">
          <section class="hero is-white is-fullheight">
            <div class="hero-body">
              <div class="container">
                <div class="columns is-vcentered reverse-columns">
                  <div
                    class="column is-10-mobile is-offset-1-mobile is-10-tablet is-offset-1-tablet is-5-desktop is-offset-1-desktop is-5-widescreen is-offset-1-widescreen is-5-fullhd is-offset-1-fullhd"
                    data-aos="fade-down"
                  >
                    <h4 class="title titled is-1 mb-6">Property</h4>
                    <h2
                      class="subtitled subtitle has-text-grey is-4 has-text-weight-normal is-family-sans-serif"
                    >
                      People deserve to discover the story of a human industry
                      that cares about its craft. PivoHub provides powerful and
                      simple software to create a digital ecosystem that
                      connects, organizes, and equips the craft beverage
                      industry. We will be the best-of-breed craft beverage
                      marketplace working with the world’s most notorious
                      artisans.
                    </h2>
                    <div class="buttons">
                      <b-button
                        class="button is-primary is-rounded"
                        to="/sell"
                        @click="showRegister = true"
                        size="is-large"
                        >Sell</b-button
                      >

                      <router-link to="/shop">
                        <b-button
                          class="button isrounded is-outlined is-rounded"
                          size="is-large"
                          >Buy</b-button
                        >
                      </router-link>
                    </div>
                  </div>
                  <div
                    data-aos="fade-right"
                    class="column is-10-mobile is-offset-1-mobile is-10-tablet is-offset-1-tablet is-4-desktop is-offset-1-desktop is-4-widescreen is-offset-1-widescreen is-4-fullhd is-offset-1-fullhd"
                  >
                    <figure>
                      <img src="@/assets/img/undraw_refreshing.svg" />
                    </figure>
                  </div>
                </div>
              </div>
            </div>
          </section>
        </div>
        <div id="Motor">
          <section class="hero is-white is-fullheight">
            <div class="hero-body">
              <div class="container">
                <div class="columns is-vcentered reverse-columns">
                  <div
                    class="column is-10-mobile is-offset-1-mobile is-10-tablet is-offset-1-tablet is-5-desktop is-offset-1-desktop is-5-widescreen is-offset-1-widescreen is-5-fullhd is-offset-1-fullhd"
                    data-aos="fade-down"
                  >
                    <h4 class="title titled is-1 mb-6">Motor</h4>
                    <h2
                      class="subtitled subtitle has-text-grey is-4 has-text-weight-normal is-family-sans-serif"
                    >
                      People deserve to discover the story of a human industry
                      that cares about its craft. PivoHub provides powerful and
                      simple software to create a digital ecosystem that
                      connects, organizes, and equips the craft beverage
                      industry. We will be the best-of-breed craft beverage
                      marketplace working with the world’s most notorious
                      artisans.
                    </h2>
                    <div class="buttons">
                      <b-button
                        class="button is-primary is-rounded"
                        to="/sell"
                        @click="showRegister = true"
                        size="is-large"
                        >Sell</b-button
                      >

                      <router-link to="/shop">
                        <b-button
                          class="button isrounded is-outlined is-rounded"
                          size="is-large"
                          >Buy</b-button
                        >
                      </router-link>
                    </div>
                  </div>
                  <div
                    data-aos="fade-right"
                    class="column is-10-mobile is-offset-1-mobile is-10-tablet is-offset-1-tablet is-4-desktop is-offset-1-desktop is-4-widescreen is-offset-1-widescreen is-4-fullhd is-offset-1-fullhd"
                  >
                    <figure>
                      <img src="@/assets/img/undraw_refreshing.svg" />
                    </figure>
                  </div>
                </div>
              </div>
            </div>
          </section>
        </div>
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

<style>
html {
  scroll-behavior: smooth;
}
.mainhero {
  background: linear-gradient(
      rgba(132, 231, 248, 0.45),
      rgba(5, 115, 158, 0.45),
      rgba(141, 206, 231, 0.45)
    ),
    url("https://thumbs.dreamstime.com/b/young-black-family-embracing-outdoors-smiling-camera-young-black-family-embracing-outdoors-smiling-camera-119401418.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.scroll {
  width: 70px;
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
.HoverServices:hover {
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
@import url("https://fonts.googleapis.com/css?family=Lato|Poppins|Kaushan+Script");
.has-vertically-aligned-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

* {
  box-sizing: border-box;
}

html {
  font-family: "Poppins", Lato, Tahoma, sans-serif;
  width: 100%;
  min-height: 100%;
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

.hero .title {
  font-family: "Kaushan Script", sans-serif;
  transform: rotate(-5deg);
  font-size: 5rem;
  color: whitesmoke;
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
