<template>
  <mdb-container class="text-center animated fadeIn">
    <h1 class="title py-4">
      Amazing App
    </h1>
    <logo />
    <h2 class="subtitle pb-4">
      MDB Vue + Nuxt.js
    </h2>
    <hr />
    <div class="links">
      <h3 class="pt-2 pb-4">Learn more:</h3>
      <a href="https://nuxtjs.org/" target="_blank" class="button--green">
        Nuxt.js
      </a>
      <a
        href="https://mdbootstrap.com/docs/vue/"
        target="_blank"
        class="button--grey"
      >
        MDBootstrap + Vue
      </a>
    </div>
  </mdb-container>
</template>

<script>
import { mdbContainer } from "mdbvue";

import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo,
    mdbContainer
  }
};
</script>

<style>
.container {
  margin: 10vh auto 0 auto;
  min-height: 90vh;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
}

.links {
  padding-top: 15px;
}
</style>
