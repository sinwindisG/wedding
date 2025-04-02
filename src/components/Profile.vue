<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > h3, div; cls: uk-animation-fade; delay: 500"
  >
    <div>
      <h3>신랑·신부 소개</h3>
      <div class="uk-child-width-1-2" uk-grid>
        <div class="profile-column">
          <div><img class="profile-img" src="/img/groom.png" /></div>
          <div>
            <span class="position-text">신랑</span><span class="name-text">신동하</span>
          </div>
          <div>1996. 08. 12</div>
          <div>서울 강동구 출생</div>
          <div>#운동러버 #IT개발자</div>
          <div>🌳</div>
          <div>나무같은 남편이 되겠습니다</div>
        </div>
        <div class="profile-column">
          <div><img class="profile-img" src="/img/bride.png" /></div>
          <div>
            <span class="position-text">신부</span><span class="name-text">유지승</span>
          </div>
          <div>1995. 08. 25</div>
          <div>경기도 남양주 은골 출생</div>
          <div>#애교쟁이 #선생님</div>
          <div>☀️</div>
          <div>햇살같은 아내가 되겠습니다</div>
        </div>
      </div>
    </div>
    <hr class="uk-divider-icon" />
  </div>
</template>

<style scoped>
.profile-column {
  text-align: center;
  color: rgba(var(--color-text-alpha), 0.8);
  font-size: 0.8rem;
}
.profile-img {
  border-radius: 50%;
  width: 80%;
  padding-bottom: 10px;
}
.position-text {
  font-size: 0.8rem;
  color: rgba(var(--color-text-alpha), 0.5);
  padding-right: 5px;
}
.name-text {
  font-size: 1rem;
  color: rgba(var(--color-text-alpha), 1);
}
</style>
