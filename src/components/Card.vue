<template>
  <div class="uk-width-1-1" uk-scrollspy="target: > h3, h4, div; cls: uk-animation-fade; delay: 500">
    <div class="card uk-text-center">
      <h3>결혼합니다.</h3>
      <h4>
        두 사람이 사랑으로 만나<br />
        진실과 이해로써 하나를 이루려 합니다.<br />
        이 두 사람을 지성으로 아끼고 돌봐주신<br />
        여러 어른과 친지분들을 모시고<br />
        서약을 맺고자 하오니<br />
        바쁘신 가운데 두 사람의 장래를<br />
        가까이에서 축복해 주시면 고맙겠습니다.<br />
      </h4>
      <div>
        <table>
          <tbody>
            <tr>
              <td>박운석</td>
              <td rowspan="2">의 장남 박상현</td>
            </tr>
            <tr>
              <td>이영화</td>
            </tr>
            <tr>
              <td>구병문</td>
              <td rowspan="2">의 차녀 구연재</td>
            </tr>
            <tr>
              <td>김길순</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <hr class="uk-divider-icon" />
  </div>
</template>

<style scoped>
.card {
  border: 1px solid white;
  border-radius: 600px 600px 0px 0px;
  width: 100%;
  max-width: 400px;
  margin: 0 auto;
  padding: 50px 0px 50px 0px;
}

table {
    margin-left:auto; 
    margin-right:auto;
    font-weight: 600;
}

td {
    padding: 5px;
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
  font-size: 0.8rem;
  margin-top: 0;
  padding: 5px;
}

* {
  font-family: "Orbit", sans-serif;
  line-height: 170%;
}
</style>
