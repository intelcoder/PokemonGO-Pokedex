# 포켓몬 고 도감
  포켓몬 고 도감 in JSON

# Elements
*   **id**: *포켓몬 아이디*
*   **num**: *포켓몬 공식 번호*
*   **name**: *포켓몬 이름*
*   **img**: *포켓몬 이미지 URL*
*   **type**: *포켓몬 타입*
*   **height**: *포켓몬 키*
*   **weight**: *포켓몬 몸무게*
*   **candy**: *진화에 필요한 캔디 겟수*
*   **egg**: *알을 까기위해 이동해야 하는 킬로미터*
*   **multipliers**: *진화이후 전투력(CP) 계산에 사용되어짐* **(NEW)**  [아래를 참조](#multipliers)
*   **weakness**: *현제 포켓몬이 약한 타입* **(NEW)**
*   **next_evolution**: *이전 진화 포켓몬 번호와 이름* **(NEW)**
*   **prev_evolution**: *다음 진화 포켓몬 번호와 이름* **(NEW)**

## Multipliers

  공식 `EvolvedCP = OriginalCP x multiplier`.

multipliers 사용 예시:
전투력이 200인 이상해씨를 진화 시키려고 한다. 이상해풀에 예상 전투력은 `365 = 200 x 1.58` CP.

만약에 두개 이상의 `multipliers` 값이 있다면 포켓몬이 진화했을 때 나올 수 있는 최대 최저 값을 의미한다.
