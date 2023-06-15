<script setup>
import Invitation from "./components/Invitation.vue";
import Card from "./components/Card.vue";
import Map from "./components/Map.vue";
import Account from "./components/Account.vue";
</script>

<template>
  <div class="wrapper">
    <div class="contents">
      <div
        uk-scrollspy="target: > div, h1, img, hr, h3, p, iframe, h4, table, ul; cls: uk-animation-fade; delay: 500"
      >
        <Invitation id="invitation" />
        <Card id="card" />
      </div>
      <Map id="map" />
      <Account id="account" />
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  padding: 10px 30px 40px 30px;
}

.contents {
  width: 100%;
  max-width: 400px;
  margin: auto;
}
</style>
