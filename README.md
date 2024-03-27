    <footer>
      <!-- radio, checkbox내 name은 맞추되 id는 각각 달라야한다. -->
      <fieldset>
        <legend>취미</legend>
        <ul>
          <li>
            <input type="checkbox" name="check" id="coding" />
            <label for="coding">잠자기</label>
            <input type="checkbox" name="check" id="exercise" />
            <label for="exercise">운동</label>
            <input type="checkbox" name="check" id="breath" />
            <label for="breath"맛집탐방</label>
            <input type="checkbox" name="check" id="travel" />
            <label for="travel">여행</label>
            <input type="checkbox" name="check" id="sleeping" />
            <label for="sleeping">강아지랑놀기</label>
            <input type="checkbox" name="check" id="reading" />
            <label for="reading">한달에한권책읽기</label>
            <input type="checkbox" name="check" id="play" />
            <label for="play">ott시청</label>
          </li>
          <li>
            <input type="radio" name="gender" id="male" />
            <label for="male">남</label>
            <input type="radio" name="gender" id="female" />
            <label for="female">여</label>
            <input type="radio" name="gender" id="secret" />
            <label for="secret">비밀</label>
          </li>
        </ul>
      </fieldset>
    </footer>
    <script>
      function submit() {
        alert("가입해주셔서 감사합니다.");
      }
      function cancel() {
        alert("다음에 봐요 :()");
        window.close();
      }
      //   window.close() 기본 function을 활용하여 알림 발송후 홈페이지를 닫는다.
    </script>
  </body>
</html>
