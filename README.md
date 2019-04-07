# 프리코스 3주차 로또 게임 
****

## 게임 규칙 

* 사용자는 처음에 로또의 가격을 입력한다 (한 장의 가격은 1000원이다.)

* 구매한 로또의 번호를 출력한다.

* 지난 주의 당첨번호와 보너스볼을 입력 받는다.

* 해당 당첨번호에 따른 구매한 로또의 당첨통계를 출력한다.

****
### 사용 예시

    구입금액을입력해주세요. 8000
    8개를구매했습니다. 
    [8,21,23,41,42,43]
    [3,5,11,16,32,38] 
    [7,11,16,35,36,44] 
    [1,8,11,31,41,42] 
    [13,14,16,38,42,45] 
    [7,11,30,40,42,43] 
    [2,13,22,32,38,45] 
    [1,3,5,14,22,4]
    
    지난주당첨번호를입력해주세요. 
    1,2,3,4,5,6 
    보너스볼을입력해주세요. 
    7
    
    당첨통계
    --------- 
    3개일치(5000원)-1개 
    4개일치(50000원)-0개 
    5개일치(1500000원)-0개 
    5개일치,보너스볼일치(30000000원)-0개 
    6개일치(2000000000원)-0개 
    총수익률은0.625입니다. 
  
#### 기능 목록

* 구입금액을 입력받아야 한다.

* 구입금액을 입력받을 때의 예외처리를 해야한다.

* 구입금액에 따른 로또의 수만큼 로또 객체를 생성해야 한다.

* 1~45까지의 숫자를 랜덤으로 6개 생성해야 한다. 

* 로또 객체의 리스트에 생성한 6개의 숫자를 저장하고 로또의 수만큼 반복한다.

* 구매한 로또번호를 출력해야 한다.

* 사용자로부터 지난주의 당첨 번호를 입력받아야 한다.

* 지난주 당첨번호의 예외처리를 해야한다.

* 사용자로부터 보너스볼을 입력받아야 한다. 

* 입력받은 보너스볼의 예외처리를 해야한다.

* 당첨 통계를 출력해야 한다.

* 수익률을 출력해야 한다.

