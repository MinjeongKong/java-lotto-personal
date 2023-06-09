## 💙 기능 목록
### 1. 로또 구매
- 로또 1장의 가격은 1000원
- 구입 금액은 1000원 단위로 입력
  - `IllegalArgumentException`
    - 1000원으로 나눠 떨어지지 않을 경우
    - 숫자가 아닌 경우

### 2. 로또 발행
- 로또 번호의 숫자 범위는 1~45
- 1개의 로또를 발행할 때 중복되지 않는 6개의 숫자를 뽑는다
  - `IllegalArgumentException`
    - 1~45 사이 숫자가 아닌 경우
    - 중복된 숫자가 있는 경우
    - 번호의 개수가 6개가 아닐 경우

### 3. 당첨 번호 추첨
- 중복되지 않는 숫자 6개를 뽑는다
  - `IllegalArgumentException`
    - 1~45 사이 숫자가 아닌 경우
    - 중복된 숫자가 있는 경우
    - 번호의 개수가 6개가 아닐 경우
- 보너스 번호 1개를 뽑는다
  - `IllegalArgumentException`
    - 1~45 사이 숫자가 아닌 경우
- 사용자가 구매한 로또 번호와 당첨 번호를 비교
- 비교한 결과에 해당하는 등수 찾기

### 4. 당첨 내역 출력
- 당첨 내역 조회
- 수익률 계산
  - 총 이익 덧셈
  - 소수점 둘째 자리에서 반올림한다

---
