# 동행복권 회차정보 API를 활용하여, 데이터 수집하기I

## Dev Info<br>
Lang : Python 3.9.9<br>
DB : mySql<br>
API : https://www.dhlottery.co.kr/common.do?method=getLottoNumber&drwNo=(원하는 회차 번호)<br>

## Concept<br>
1. 회차별 로또 정보 조회<br>
2. API를 통해 받아온 결과를 DB에 적재<br>
3. DB에 적재되어있는 회차를 조회 후 신규 회차가 발생하면, 추가 적재<br>

## Response Info<br>
1. drwNo : 추첨 회차<br>
2. drwNoDate : 추첨 일<br>
3. drwtNo1 : 번호 1<br>
4. drwtNo2 : 번호 2<br>
5. drwtNo3 : 번호 3<br>
6. drwtNo4 : 번호 4<br>
7. drwtNo5 : 번호 5<br>
8. drwtNo6 : 번호 6<br>
9. bnusNo : 보너스 번호<br>
10. firstAccumamnt : 1등 총액<br>
11. firstPrzwnerCo : 1등 당첨자 수<br>
12. firstWinamnt : 1등 당첨액<br>
13. totSellamnt : 판매 금액<br>
14. returnValue : 결과 값<br>

