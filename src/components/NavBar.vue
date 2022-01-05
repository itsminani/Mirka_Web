<template>
  <b-navbar>
    <template #brand>
      <b-navbar-item tag="router-link" :to="{ path: '/' }">
        <img
          src="../assets/logo.png"
          alt="Lightweight UI components for Vue.js based on Bulma"
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
              <b-icon role = "button" icon="translate"> </b-icon>
            </template>

            <b-dropdown-item aria-role="listitem">Kinyarwanda</b-dropdown-item>
            <b-dropdown-item aria-role="listitem"
              >English</b-dropdown-item
            >
            <b-dropdown-item aria-role="listitem"
              >French</b-dropdown-item
            >
          </b-dropdown>

          <!-- <a class="button">
          </a> -->
        </div>
      </b-navbar-item>
    </template>
  </b-navbar>
</template>
