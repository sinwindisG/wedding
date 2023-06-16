<script setup>
import Invitation from "./components/Invitation.vue";
import Card from "./components/Card.vue";
import Calendar from "./components/Calendar.vue";
import Gallery from "./components/Gallery.vue";
import Map from "./components/Map.vue";
import Account from "./components/Account.vue";
</script>

<template>
  <div>
    <div class="wrapper">
      <div class="contents">
        <div
          uk-scrollspy="target: > div, h1, img, hr, h3, p, iframe, h4, table, ul; cls: uk-animation-fade; delay: 500"
        >
          <Invitation />
          <Card />
        </div>
        <Calendar />
        <Gallery />
        <Map />
        <Account />
      </div>
    </div>
    <div class="uk-text-center"><img class="pixel" src="/img/footer.png" /></div>
    <div class="footer"></div>
  </div>
</template>

<style scoped>
.footer {
  background-color: #bbbbcc;
  height: 30px;
  overflow: hidden;
  text-align: center;
}

.pixel {
  image-rendering: pixelated;
  position: relative;
  bottom: -24px;
}

.wrapper {
  padding: 10px 30px 10px 30px;
}

.contents {
  width: 100%;
  max-width: 400px;
  margin: auto;
}
</style>
