<template>
  <div
    class="uk-width-1-1"
    uk-scrollspy="target: > h3, div; cls: uk-animation-fade; delay: 500"
  >
    <div>
      <h3>시월의<br />마지막 일요일.</h3>
      <div class="calendar uk-text-center uk-overflow-auto">
        <table>
          <caption>
            <span class="caption">2023. 10</span>
          </caption>
          <colgroup>
            <col style="width: 5%" />
            <col style="width: 5%" />
            <col style="width: 5%" />
            <col style="width: 5%" />
            <col style="width: 5%" />
            <col style="width: 5%" />
            <col style="width: 5%" />
          </colgroup>
          <thead>
            <tr>
              <th scope="col">일</th>
              <th scope="col">월</th>
              <th scope="col">화</th>
              <th scope="col">수</th>
              <th scope="col">목</th>
              <th scope="col">금</th>
              <th scope="col">토</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="holiday">1</td>
              <td>2</td>
              <td class="holiday">3</td>
              <td>4</td>
              <td>5</td>
              <td>6</td>
              <td>7</td>
            </tr>
            <tr>
              <td class="holiday">8</td>
              <td class="holiday">9</td>
              <td>10</td>
              <td>11</td>
              <td>12</td>
              <td>13</td>
              <td>14</td>
            </tr>
            <tr>
              <td class="holiday">15</td>
              <td>16</td>
              <td>17</td>
              <td>18</td>
              <td>19</td>
              <td>20</td>
              <td>21</td>
            </tr>
            <tr>
              <td class="holiday">22</td>
              <td>23</td>
              <td>24</td>
              <td>25</td>
              <td>26</td>
              <td>27</td>
              <td>28</td>
            </tr>
            <tr>
              <td class="holiday circle">29</td>
              <td>30</td>
              <td>31</td>
              <td></td>
              <td></td>
              <td></td>
              <td></td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <hr class="uk-divider-icon" />
  </div>
</template>

<style scoped>
.calendar {
  width: 100%;
  font-size: 0.8rem;
}

.caption {
  font-weight: 700;
}

.weddingday::before {
  background-color: #ffffff00;
  position: absolute;
  height: 30px;
  width: 30px;
  border-radius: 50%;
  border: 1px solid #ffffffaa;
  color: #fff;
  text-align: center;
}

.circle {
  width: 25px;
  height: 25px;
  border-radius: 51%;
  border: 1px solid #ffffffaa;
  display: inline-block;
}

.holiday {
  color: #fcb8b8e1;
}

table {
  margin-left: auto;
  margin-right: auto;
  color: #ffffffcc;
  padding: 15px;
  border-radius: 50px;
}

th, td {
  padding: 5px;
}
</style>
