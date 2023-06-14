<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > h3, div; cls: uk-animation-fade; delay: 500"
  >
    <div>
      <h3>오시는 길</h3>
      <div class="uk-accordion-content">
        <p>
          서울대학교 이라운지<br />
          서울 관악구 관악로 1 서울대학교 관악캠퍼스 310동
        </p>
        <div>
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3167.5181054418454!2d126.94835137581916!3d37.448487330888625!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357c9ff8b1cc7f7d%3A0x76ce756427c67027!2z7J2065287Jq07KeAIOybqOuUqe2ZgCDshJzsmrjrjIDsoJA!5e0!3m2!1sko!2skr!4v1686755115485!5m2!1sko!2skr"
            width="100%"
            height="300"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          ></iframe>
        </div>
      </div>
    </div>
    <hr class="uk-divider-icon" />
  </div>
</template>

<style scoped>
h3 {
  color: white;
  letter-spacing: 10px;
  font-size: 1.2rem;
  font-weight: 700;
}

* {
  font-family: "Orbit", sans-serif;
  line-height: 170%;
}
</style>
