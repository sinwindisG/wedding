<script setup>
import Invitation from "./components/Invitation.vue";
import Card from "./components/Card.vue";
import Map from "./components/Map.vue";
import Account from "./components/Account.vue";
</script>

<template>
  <div class="wrapper">
    <div class="contents">
      <Invitation />
      <Card />
      <Map />
      <Account />
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  padding: 30px 30px 70px 30px;
}

.contents {
  width: 100%;
  max-width: 400px;
  margin: auto;
}
</style>
