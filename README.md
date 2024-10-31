# 로또

## 프로젝트 소개
**간단한 로또 발매기**를 구현한 프로그램  
사용자가 로또 구입 금액을 입력하면 금액에 해당하는 만큼 로또를 발행한다.  
당첨 번호 6개와 보너스 번호도 입력받은 후에 사용자에게 당첨 통계를 보여준다.  
당첨 통계에는 몇 개가 일치하는지와 가격에 따른 갯수로 표현하고 총 수익률도 계산하여 보여준다.


## 주요 기능
- **로또 번호 생성** : 입력받은 금액에 맞춰 로또 번호를 자동으로 생성한다.
- **당첨 번호 및 보너스 번호 설정** : 사용자의 입력을 통해 당첨 번호와 보너스 번호를 받아 추첨 결과와 비교한다.
- **당첨 결과 확인** : 사용자가 구매한 로또 번호와 당첨 번호를 비교하여 일치하는 숫자에 따라 당첨 등수를 판단하여 출력한다.
- **수익률 계산** : 사용자가 투자한 금액 대비 수익률을 계산하여 퍼센트로 출력한다.
- **에러 처리** : 잘못된 입력이 발생할 경우 오류 메시지를 출력한 후 재입력받는다.


## 기능 목록
1. 로또 구입 금액 입력
   - [ ] 사용자에게 구입 금액을 입력받는다.
   - [ ] 유효하지 않은 경우 `IllegalArgumentException`을 발생시키고  `[ERROR]`로 시작하는 메시지를 출력한다.
2. 로또 발행 및 출력
   - [ ] 입력받은 금액에 따라 1000원당 하나의 로또를 발행한다.
   - [ ] 각 로또 번호는 1~45 사이의 중복되지않은 6개의 숫자이다.
   - [ ] 각 로또 번호를 오름차순으로 출력한다.
3. 당첨 번호 & 보너스 번호 입력
   - [ ] 6개의 숫자를 쉼표로 구분하여 입력받는다.
   - [ ] 보너스 번호는 당첨 번호와 중복되지 않는 1개의 숫자로 입력받는다.
   - [ ] 유효하지 않은 경우 `IllegalArgumentException`을 발생시키고  `[ERROR]`로 시작하는 메시지를 출력한다.
4. 당첨 결과 판별 및 출력
   - [ ] 발행된 로또 번호와 당첨 번호를 비교하여 일치 개수를 센다.
   - [ ] 일치 갯수에 따른 당첨 로또 갯수를 출력한다.
5. 수익률 계산 및 출력
   - [ ] 구입 금액과 당첨 금액을 바탕으로 수익률을 계산한다.
   - [ ] 소수점 둘째 자리에서 반올림하여 출력한다.



## 입력 예외 상황
- [ ] 구입 금액이 정수가 아닌 경우
- [ ] 구입 금액이 0이거나 음수인 경우
- [ ] 구입 금액이 1000원 단위가 아닌 경우
- [ ] 로또 번호 입력이 1~45 범위를 벗어나는 경우
- [ ] 당첨 번호와 보너스 번호가 중복되는 경우
- [ ] 당첨 번호가 중복되는 경우
- [ ] 당첨 번호가 6개가 아닌 경우

