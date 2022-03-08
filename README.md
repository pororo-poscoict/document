# [글로벌 SCM 사업부]

## 1조 소개
+ 팀명 : pororo
+ 프로젝트 주제 : MSA 환경을 기반으로 한 mini 진행관리 시스템 개발 구축
+ 프로젝트 기간 📆 : 2022.03.07 ~ 2022.05.24
### 👨‍👦‍👦조원
   |천계환   |경선재   |김지혜   |이원석   |
   |---|---|---|---|
   |bbororo|luppy|eddy|poby|
   |![bbororo](./image/bbororo.jpg)|![luppy](./image/luppy.jpg)|![eddy](./image/eddy.jpg)|![poby](./image/poby.jpg)|
   |[천계환 github 주소](https://github.com//CheonGyeHwan)|[경선재 github 주소](https://github.com//SEONJAEK)|[김지혜 github 주소](https://github.com/jihye1215)|[이원석 github 주소](https://github.com//wonseoks-lee)|‍

### ✔️ 조별 규칙
   1. 모르는거 바로 물어보기
   2. 가능한 할 일은 같이 있을 때 끝내는 것을 목표로 하기
   3. 7시 30분까지 모이기‍
   4. 기분 좋게 코딩하자
   5. 하루에 3번 웃자
   6. 1주일에 1번은 카페가서 이야기하자(30분정도)
   
--------------------------------------------------------------------
## 프로젝트 회의 내용(3/7일)
### 💡 Project Architecture
![Project Architecture](./image/fn1.PNG)
![Project Architecture](./image/fn.PNG)
+ o/s : 주문(order), 주문번호, 납기, 회사명 등
+ 재료 실적 : 제철소에서 정보가 오는데 테스트 화면을 만들어서 공정 순서대로 버튼을 누르면 하나씩 API가 날라가면서 없던 재료가 생기고 추가되는 등의 데이터 변동
+ 소재충당/목전(목적전환) 
   + 예) 스타벅스에 보낼 커피 원두를 만들던 중 질이 좋지 않을 경우 버리기 아까우니까 조금 더 저렴한 브랜드를 찾아서 저렴한 브랜드에 대신 보내는 것을 목전(목전전환)이라고 한다.
+ 구입재 : 구입해오는 소재
   + 외부에서 어느정도 만들어진 slab, coil 같은 것을 작은 철강회사에서 구매해오는 느낌(이미 만들어진 제품을 사오는 것)
   -> 그러면 DB에 insert되기 때문에 없던 데이터가 생긴다.
+ 추가 기능 후보
   1. 현재 엑셀에 import하는 것이 번거롭고 불편하기 때문에 엑셀에서 바로 복사해서 붙여넣을 수 있는 기능이 있으면 편리할 것 같다.