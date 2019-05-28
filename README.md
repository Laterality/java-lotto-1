# java-lotto
로또 미션 진행을 위한 저장소

## 기능 요구사항

* 로또 생성
    - [x] 1 ~ 45 사이의 임의의 정수 6개로 로또를 생성한다.
* 당첨 통계
    - [x] 당첨 번호와 일치하는 로또를 찾아 일치하는 개수 별 통계와 수익률을 계산한다.
* 사용자 인터페이스(콘솔)
    * 입력
        - [x] 로또 구입 금액을 입력받는다.
            - [x] 최소한 한 장을 살 수 있어야 한다.
            - [x] 구입금액이 장당 가격으로 나눠 떨어지지 않는 경우 가능한 많은 로또를 구입한다.
        - [x] 수동으로 구매할 로또 수를 입력받는다.
            - [x] **예외**: 수동으로 구매하는 숫자가 구입 금액을 초과하는 경우
        - [x] 수동으로 구매하는 각 로또의 숫자를 입력받는다.
        - [x] 당첨 번호를 입력한다.
            - [x] 1 ~ 45 사이의 정수여야 한다.
            - [x] 쉼표로 구분한다.
            - [x] 순서는 무관하며, 각 숫자는 중복되선 안된다.
    * 출력
        - [x] 구입한 로또 번호를 출력한다.
        - [x] 당첨 통계를 출력한다.