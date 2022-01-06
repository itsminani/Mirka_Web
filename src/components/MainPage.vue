<template>
  <div>
    <div class="">
      <div>
        <section class="hero is-success is-fullheight has-background">
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
                class="services"
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
                  <li :class="active"><a href="#Medical">Medical</a></li>
                  <li :class="active"><a href="#Property">Property</a></li>
                  <li :class="active"><a href="#Motor">Motor</a></li>
                </ul>
              </div>
            </nav>
          </div>
        </section>
      </div>
      <div class="mainServices">
        <div id="Medical">Medical</div>
        <div id="Property">Property</div>
        <div id="Motor">Motor</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            active: ""
        }
    },
};
</script>

<style>
html {
  scroll-behavior: smooth;
}
.hero {
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

.services {
  animation-name: updown;
  animation-duration: 2s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
  text-decoration: underline;
  cursor: pointer;
  transition: ease-in-out 2.3s;
}
.services:hover {
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
</style>
