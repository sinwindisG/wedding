<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > div; cls: uk-animation-fade; delay: 500"
  >
    <div>
      <h3>마음 전하실 곳</h3>
      <div class="uk-accordion-content">
        <p>
          비대면으로 축하를 전하고자 하시는 분들을 위해 계좌번호를 기재하였습니다.
          너그러운 마음으로 양해 부탁드립니다.
        </p>
        <div>
          <ul uk-accordion="multiple: true">
            <li>
              <a class="uk-accordion-title">신랑측</a>
              <div class="uk-accordion-content">
                <dl class="uk-description-list">
                  <dt>신랑</dt>
                  <dd>1002-854-632895<br />우리은행 박상현</dd>
                </dl>
              </div>
            </li>
            <li>
              <a class="uk-accordion-title">신부측</a>
              <div class="uk-accordion-content">
                <dl class="uk-description-list">
                  <dt>신부</dt>
                  <dd>110-535-223219<br />신한은행 구연재</dd>
                </dl>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.uk-accordion-title {
  color: white;
  letter-spacing: 10px;
  font-size: 1rem;
  font-weight: 700;
  color: #ffffffd0;
}

.uk-description-list {
  background-color: #ffffff0c;
  border-radius: 10px;
  padding: 10px;
}

a:hover {
  color: #ffffffa7;
}

dt {
  color: white;
  letter-spacing: 5px;
  font-size: 0.9rem;
  font-weight: 700;
  color: #ffffffd0;
}

dd {
  color: white;
  font-size: 0.9rem;
  color: #ffffffd0;
}

h3 {
  color: white;
  letter-spacing: 10px;
  font-size: 1.2rem;
  font-weight: 700;
}

h4 {
  color: white;
  letter-spacing: 2px;
  font-size: 0.9rem;
  margin-top: 0;
}

* {
  font-family: "Orbit", sans-serif;
  line-height: 170%;
}
</style>
