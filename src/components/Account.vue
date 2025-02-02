<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > div; cls: uk-animation-fade; delay: 500"
  >
    <div>
      <h3>마음 전하실 곳</h3>
      <div class="uk-accordion-content">
        <p class="content-text">
          비대면으로 축하를 전하고자 하시는 분들을 위해 계좌번호를 기재하였습니다.
          너그러운 마음으로 양해 부탁드립니다.
        </p>
        <div>
          <ul uk-accordion="multiple: true">
            <li>
              <a class="uk-accordion-title">신랑측</a>
              <div class="uk-accordion-content">
                <dl class="uk-description-list uk-description-list-divider">
                  <dt>신랑</dt>
                  <dd>1002-565-573358<br />우리은행 신동하</dd>
                  <dt>신랑어머니</dt>
                  <dd>1002-441-166085<br />우리은행 안혜선</dd>
                </dl>
              </div>
            </li>
            <li>
              <a class="uk-accordion-title">신부측</a>
              <div class="uk-accordion-content">
                <dl class="uk-description-list uk-description-list-divider">
                  <dt>신부</dt>
                  <dd>655601-04-395879<br />국민은행 유지승</dd>
                  <dt>신부어머니</dt>
                  <dd>947801-01-144199<br />국민은행 최지우</dd>
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
.uk-accordion-content {
  color: #ffffffd0;
}

.uk-accordion-title {
  letter-spacing: 10px;
  font-size: 1rem;
  font-weight: 700;
  color: #ffffff;
}

.uk-description-list {
  background-color: #ffffff0c;
  border-radius: 10px;
  padding: 20px;
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
  color: #ffffffcc;
}
</style>
