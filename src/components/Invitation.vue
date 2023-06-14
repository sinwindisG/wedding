<template>
  <div class="uk-width-1-1" uk-scrollspy="target: > h1, img, hr, div; cls: uk-animation-fade; delay: 500">
    <div>
      <div class="uk-text-center">
        <h1>wedding invitation</h1>
      </div>
      <img
        src="/img/main.png"
      />
      <hr class="uk-divider-icon" />
      <div class="uk-text-center">
        <h3>
          박상현·구연재<br />
          결혼합니다
        </h3>
        <h4>
          2023년 10월 29일, 일요일 낮 2시<br />
          서울대학교 이라운지
        </h4>
        <hr class="uk-divider-icon" />
      </div>
    </div>
  </div>
</template>

<style scoped>
h1 {
  color: white;
  /*font-family: 'Dawning of a New Day', cursive;*/
  font-family: "Mr De Haviland", cursive;
}

h3 {
  color: white;
  letter-spacing: 10px;
  font-size: 1.2rem;
  font-weight: 800;
}

h4 {
  color: white;
  letter-spacing: 1px;
  font-size: 0.9rem;
  margin-top: 0;
}

* {
  font-family: "Orbit", sans-serif;
  line-height: 170%;
}
</style>
