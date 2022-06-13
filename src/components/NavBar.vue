<template>
  <b-navbar id="navbar">
    <template #brand>
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        <img
          src="../assets/logo.png"
          alt="Mirka Logo"
        />
      </b-navbar-item>
    </template>
    <template #start>
      <b-navbar-item href="#"> Home </b-navbar-item>
      <b-navbar-item href="#"> Documentation </b-navbar-item>
      <b-navbar-dropdown label="Info">
        <b-navbar-item href="#"> About </b-navbar-item>
        <b-navbar-item href="#"> Contact </b-navbar-item>
      </b-navbar-dropdown>
    </template>

    <template #end>
      <b-navbar-item tag="div">
        <div class="buttons" style="">
          <b-dropdown position="is-bottom-left" aria-role="list">
            <template #trigger>
              <b-icon role="button" icon="translate"> </b-icon>
            </template>

            <b-dropdown-item aria-role="listitem">Kinyarwanda</b-dropdown-item>
            <b-dropdown-item aria-role="listitem">English</b-dropdown-item>

            <b-dropdown-item aria-role="listitem">French</b-dropdown-item>
          </b-dropdown>

          <!-- <a class="button">
          </a> -->
        </div>
      </b-navbar-item>
    </template> 
  </b-navbar>
</template>


<script>
var prevScrollpos = window.pageYOffset;
window.onscroll = function() {
  var currentScrollPos = window.pageYOffset;
  if (prevScrollpos > currentScrollPos) {
    document.getElementById("navbar").style.top = "0";
  } else {
    document.getElementById("navbar").style.top = "-50px";
  }
  prevScrollpos = currentScrollPos;
}
</script>
<style>
#navbar {
  position: fixed; /* Make it stick/fixed */
  top: 0; /* Stay on top */
  width: 100%; /* Full width */
  transition: top 0.3s; /* Transition effect when sliding down (and up) */
}
</style>