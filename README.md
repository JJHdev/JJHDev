# 🔭 장정현의 개발자일지
## 이글은 어떻게 성장해오고 어떤 고민을 가지며 어떻게 수행해가는지 기록하는 일지입니다.


![본인ID's github stats](https://github-readme-stats.vercel.app/api?username=JJHDev&show_icons=true)
[![본인ID's github stats](https://github-readme-stats.vercel.app/api/top-langs/?username=JJHDev&show_icons=true&hide_border=true&title_color=004386&icon_color=004386&layout=compact)](https://github.com/JJHDev)


### 개발자 계획
```sh
   ※ ✨(완료) / 🌱(진행중) / 💬(미 진행) / 🤔(실패)
  1.  (✨)23년 11월     정보처리기사 실기 취득
  2.  (✨)24년 1월      국비학원에서 배운내용 복습하기
  3.  (✨)24년 2~5월    Spring(김영한님 강의 듣기 기초, 핵심, MVC) --> 최소 3회독
  4.  (✨)24년 4월      docker & Aws 배포하기 (프리온보딩 백엔드 과정 신청)
  5.  (✨)24년 4월      자바 ORM 표준 JPA 프로그래밍 공부 (김영한님 책으로 공부)
  6.  (✨)24년 4~5월    sqld자격증 취득 (유선생, 노랭이책) --> 개발이사님께서 SQL공부는 꾸준히 하라 추천하셔서 계속 공부 해야겠다 다짐.
  7.  (🌱)24년 5월      개인 프로젝트 진행. (프로젝트 설정, CI-CD구성, Docker 배포, AWS 배포 까지 일단 예정, 프로젝트 어떻게 할지는 정했음.)
  8.  (🌱)24년 5월      코딩테스트 책 사서 공부 (매일 최소 1시간씩이라도..)
  9.  (🤔)24년 6월      석사 or 학사 (백엔드 관련 학과 입학) --> 석사대신 학사를 주변에서 많이 추천하였음. >> 2학기 지원떨어져 내년 입학 도전
  10. (✨)24년 7월      HTTP 인터넷 강의 수강
  11. (✨)24년 8월      MVC패턴 고급편 수강
  12. (💬)24년 10월      팀플 프로젝트 진행.

```
<br/>

### 1차 공부 목표 과목
```sh
1.1 운영체체
   - 혼자 공부하는 컴퓨터 구조+운영체제 (기초), 504p, 2022.8 
    plan: 컴퓨터 구조 파트는 깊게 들어가지 말고 개념만 익히고 os 파트에 집중할 것
1.2 자료구조
   - 코딩테스트용 자료구조 및 알고리즘 
1.3 네트워크
   - 컴퓨터 네트워킹 하향식 접근(기본)
   - HTTP 완벽 가이드 (HTTP) *책 or  모든 개발자를 위한 HTTP 웹 기본 지식 (강의)
1.4 DB
   - sqld or sqlp 관련 자격증 따기위한 책을 사면 괜찮을 것 같음. or
   - Real MySQL 8.0 (MySQL 특화 RDB 기본서), 516p + 760p, 2021.9
```
<br/>

### 2차 공부 목표 과목
```sh
2.1 자바
   - 이것이 자바다 (기본서), 1008p, 2022.9
2.2 방법론/개념
   - 클린 코드
   - 객체지향의 사실과 오해
```
<br/>

### 3차 공부 목표 과목
```sh
3.1 스프링
   - 토비의 스프링 3.1, 1720p, 2012.
   plan : 토비의 스프링 3.1 2권은 굳이 안봐도 됨, 궁금하면 1,2,3장 세부 목차만 구글링으로 검색해서 볼 것
3.2 JPA
   - 자바 ORM 표준 JPA 프로그래밍, 736p, 2015.7
```
<br/>

### 익혀야할 기술
```sh
1. CRUD
2. REST API
3. JWT 
  --> 세션 대체용도인 토큰
4. Docker
5. Swagger
6. ERD 설계
  --> Table, Db 설계
  --> 트래픽이 몰렷을때 쿼리가 잘 작동하는지?
  --> TypeOrm (SQL 잘 아는 상태에서 사용할 것)
7. AWS
  --> 클라우드 사용 할 줄 알아야 한다.
  --> EC2 (VPC1), RDS (VPC2)
8. REST API 설계 
9. RDBMS
10. TDD
11. NoSql
12. 심화 (쿠버, 카프카, 레디스, 스프링클라우드, MSA)
```
<br/>

### 코테 준비
```sh
코테도 꾸준히 공부하기
1. 코딩테스트는 기본 유형을 익히는게 우선 유형내용을 익히고 -> 대표문제를 푸는 식으로 접근
2. 대표 문제를 풀고나서 양치기 

----- 대표 유형
  -. 완전탐색
  -. 구현/시뮬레이션
  -. DFS/BFS
  -. 문자열/해시테이블
  -. 힙/다익스트라
  -. DP (어렵고 많이는 안나옴, 후 순위)

```
<br/>



# 2024년
### 2024년 04월 05일
```sh
위의 계획에서 스프링강의, docker &Aws, JPA의 책으로 공부하면서 스스로 프로젝트의 구현을 해보고 싶다 느꼇음. 그리하여 개발자 지인
두명에게 조언을 구하여 사이드프로젝트를 해보고싶다고 이야기 하였는데 크게 고민중인 부분은 다음과 같았다.
1. 개인프로젝트 구현
  -. 내가 사용하고싶었던 내용등 (스프링부트, Docker, Swagger, ERD및 REST API설계, AWS 등등 다양한 기술들을 사용할수 있다.)
  -. 책에서 저 모든 기능들을 세부적으로 공부하면서 왜 이렇게 구현했을까? 이 기술에대한 고민 등을 녹여내는 책이 없다고 생각하여 관련된
     프로젝트를 구현하며 만들고 싶었다.
  -. 구현할 프로젝트는 나만의 홈페이지다.
      1. 메모장 효과
      2. 네이버 길찾기
      3. chatGTP 연동
      4. 스케쥴관리
      5. TO-List 
      6. 돈관리 (은행 계좌 연동) 등
      내가 자주 사용하는 기능들을 모아놓으며 계정으로 하나의 홈페이지에서 모든걸 사용가능하도록 구현한 홈페이지다. 추후에 필요한 기능은
      계속 추가할 예정으로 사용됨.

2. 팀플 프로젝트 구현
  -. 두명다 추천한건 팀플 프로젝트. 그 이유로는 협업의 중요성도 있고, 프로젝트의 목적이 중요하다고 한다. (수익성 포함) 그래서 팀플 프로
     젝트를 추천하였다.

그래서 개인프로젝트와 팀플프로젝트 뭘할까 고민중에 일단 개인프로젝트를 진행하면서 어느정도 안정기에 접혀들면 시간날때마다 계속 수정하고
그때 팀플프로젝트를 하기로 생각 했다.
```
<br/>


### 2024년 03월 15일
```sh
그 후에 진행한 프로젝트는 문화관광연구원 평가지원시스템 웹사이트 기능 고도화작업.
  1. 개발방식이 애자일 방식으로 개발을 진행하였음. (솔직히 말이 애자일 방식이지.. 매주 정해진 시간에 회의하고 고객사에 고쳐달라는거
     계속 고치는 식이였음.)
    --> 가장 크게 느낀점은 앞으로 개발하면 크게 틀을 만들어 놓고 그 안에서 개발을 해야겠다고 느꼈다. 사수가 하자는 대로 해서 어쩔수
        없긴 했지만, A기능을 구현하면 B기능으로 바꿔달라 이야기하고 다시 A_ver2 고쳐달라 요청, B_ver2요청 하여 총 7번까지 수정하
        였으며, 문서화 기록을 자세히 안해놓으면 그런적 없다 이야기 하고 소통이 너무 힘들었음.
    --> 일하다가 도중에 느낀건 고객사에서도 자세히 모르니까 어떻게 해야할지 모르니까 그런다는 것을 깨닳았다. 그래서 예시템플릿, 개발자
        입장에서 아닌 고객사 입장에서 설명, 가시화된 예시, 전체 프로세스의 소통 등 확실하게 이야기 하면서 진행하는게 상대방과 개발자
        에게 중요한 것임을 배우며 그렇게 일하니 상대방이 많이 좋아하는것을 깨닳았음.. 확실히 개발자가 더 힘들어야 고객이 편하다...

  2. 개발인원의 부족
    --> 개발인력은 2명인데 실제로 혼자서 기능을 다 구현하였음. 다른 인원은 다른 프로젝트때문에 할애할 시간이 부족하여 혼자 진행 하였는데
        고객사와 소통, 개발, DB이관, Was배포 등 혼자서 하다보니 많은 것을 배운것을 느꼇음.
    --> 그치만 기능 구현하고, 개발서버에 Tomcat(window환경)에 배포하고, 실제 운영서버 배포시 운영Db서버에 Db이관하고, Was서버에 있는
        tomcat에 프로젝트 배포하였는데 수박의 겉햝기 정도로만 아는것 같다고 느껴 새롭게 공부해야겠다. 느꼇음.
```
<br/>

# 2023년

### 2023년 09월 01일
```sh
입사 당일날 프로젝트에 투입되었는데 농업정책보험금융원의 웹사이트를 만드는것에 투입되고 9월 1일까지 작업을 진행하였다.
  1. 맨처음에 담당 개발이사님과 면담의 시간을 가지게 되었는데 2~3년차 개발자를 요청하였는데 신입 개발자가 투입되어 어차피 1주일만 하다가
     다른 프로젝트에 배정될 것이다 이야기 해주셨음.
    --> 꼭 이 프로젝트를 하고 싶어서 매일 저녁 11시까지 프로젝트가 끝날때까지 남아서 일을 했음.

  2. 클라이언트단이 JS위주로 작성되어있어서 코드를 파악하는게 너무 힘들었음. (JSP를 사용하는데 JSP에 내용이 form은 없고 그자리에 DIV
     하나만 있었음..)
    -->

  3. 이사님이 작성해주신 스케쥴대로 작업을 하니 편했음.
    --> 이사님이 작성해주신 스케쥴대로 하면 딱 저녁 5시쯤 되면 기능을 완료하였다. 기능구현을 많이 하고싶어 매일 저녁 11시까지 남아서
        일을 했는데 결국 맡은 업무의 150%업무량을 해내어 결국 인정받았음.

  4. 학원에서 배운거 밖에 없는데 바로 대국민 홈페이지를 개발하게 되어 너무 떨렸음..
    --> ✨어떻게 코드를 작성해야 할까?? 어떻게 해야 설계를 클린코드이고 주석을 어떻게 달아야 사람들이 보기 편할까?? 이 고민을 가장
        많이 했음 이사님에게 코드규칙을 직접 배우며 한단계 성장한다는 느낌을 들었음. 추후 클린코드란 책을 알게되고 공부중임.✨

  5. 이사님께서 하신 말씀은 항상 기능을 많이 만드는게 중요한게 아니다 오류가 발생하지 않아야 하며, 남들이 보기 편하고 오해가 없도록
     오해없이 코드를 작성해야 한다고 매일 당부해주셨음.
    ✨--> 이 부분이 가장 크게 깨닳았음. 오픈 후 내코드에서는 오류가 발생하지 않았는데 다른 사람들의 코드에서 오류가 발생하였는데 오히려
        시간을 더 잡아먹게 되었다.  주석, 코드규칙, 사소한 오류라도 발생하지 않도록 계속 검토해야 한다는 것을 배웠음.✨

```
<br/>

### 2023년 05월 08일
```sh
1.학원에서 진행했던 3차프로젝트의 기능을 가장 많이 구현하였으며 일주일 남기고 완성하였음.
2.의욕을 좋게 봐줘 멘토링을 해줬던 기업으로 취직을 할 수있게 되었다. 
```
<br/>

### 2023년 04월 13일
```sh
학원을 다니면서 결심한 규칙을 세우며 지켰다. 
1. 매일 09~22시까지 공부하기. 22시~ 23시까지 운동하기 23시 ~ 24시까지 복습하기.
2. 프로젝트는 항상 내가 더 많은 기능을 구현하자.
3. 선생님에게 실력을 인정받자.
```
<br/>

### 2023년 03월 13일 ~ 2023년 04월 13일
```sh
 3. GIS 기반 리포팅 시스템 구축 (개인 프로젝트)
  기능구현     : 1. DB 설계및 파이썬을 이용한 CSV파일 DB 입력
                2. VWorld, OpenLayers를 이용한 지도및 추가 기능구현
                3. 날짜, 지역(시도, 시군구)에 따라 GeoServer에 필터링 전달하여 CSS를 받 레이어 변경
                4. SHP파일을 GeoServer에 업로드하는 자바코드 구현 (connection, 업로드 , close)후 Jar파일로 만들어 Python으로 구동 
  WHY?        : 개발자는 새로운 기술을 배우는 법을 배워야 한다 생각하였으며, 지도라는 기능을 어떻게 구현할지 감도 안오며 구현하고 싶었음.
  Trouble     : 1. OpenLayers를 구현하며 여러 기능을 겹쳐서 사용하였다. 그러다 보니 코드가 너무 지저분해졌음.
                2. 멘토링님이 주신 자료의 버전이 전부 안맞아 호환충돌
  해결        : 1. 공통기능은 함수로 구현하여 코드 중복 최소화, 자세한 주석문구 사용하여 코드가 전보다 간결해졌음.
                2. Java, tomcat, PostGreSql, Qgis 버전이 안맞아서 계속 충돌이 발생하여 API문서를 보며 하나씩 버전을 계속 맞춰갔음.
```
<br/>

### 2023년 02월 20일 ~ 2023년 03월 10일
```sh
 2. Auction
  기능구현     : 1. 메인상품등록
                2. 경매 투찰
                3. 경매 자동낙찰시 자동 쪽지 기능
                4. 결제기능 
  WHY?        : 실시간으로 운영되는 홈페이지를 구현하고 싶었으며, 결제기능을 구현하고 싶었음.
  Trouble     : 1. 20일 안에 구현 완료 해야 되어 시간이 너무 부족하였음.
                2. 메인상품 등록후 판매자가 상품을 등록하는건 다른팀원이 구현하고 투찰과 낙찰은 내가 구현하였는데, 소통이 중요하였음.
  해결        : 1. 첫 일주일은 DB 설계, 기능 기획, 파트분배 으로 시간을 사용하고 2주일동안 매일 새벽 3~4시까지 기능을 구현하여 겨우 완료할수 있었음.
                2. 팀원 집에서 마지막 4일동안 같이 지내면서 계속 소통하면서 작업진행 (브라우저단과 서버단을 동시에 개발하면서 하여 간단한 소통으로 진행하기 어려웠음.)
```
<br/>

### 2023년 01월 10일 ~ 2023년 02월 10일
```sh
 1. ERD System (기술팀장)
  기능구현     : 1. 로그인
                2. 사원조회및 사원관리
                3. 쪽지 보내기 기능
                4. 부서관리 기능 구현
  WHY?        : CRUD를 많이 사용하고 경험해봄으로써 코드구현에 익숙해지고 싶어, 프로젝트 주제 선정
  Trouble     : 배운지 3개월밖에 안되다 보니 각자 맡은 파트에 어려움을 겪는 팀원들이 있음.
  해결        : 팀원들이 모르는 내용은 방과후 시간에 다들 모아서 내가 알고 있는 부분을 알려주고, 못따라오는 팀원은 코드를 보며 같이 해결
```
<br/>



# 2022년

### 2022년 10월 25일
```sh
KH, 중앙정보처리학원등 여러 학원의 면접을 보고 OKKY홈페이지에서 다양한 정보를 보면서 중앙정보처리학원에서 개발자로 공부하기로 마음을
먹었다. 
```
<br/>

### 2022년 9월 1일
```sh
지인중에 IT회사를 창업한 친구, ssafy에서 멘토링을 하는 지인에게 물어보며 만 나이 30세 개발자로 시작하는데 너무 늦은건 아닐지 매일 물어보며
 생활코딩에서 경험해보라는 조언을 얻었다. 10월 1일까지 스스로 공부하면서 개발자라는 직책의 꿈을 꾸게 되었다.
```
<br/>









<!--
**JJHdev/JJHDev** is a 🌱✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
ㅁㄴㅇㅁㄴㅇㅁㄴㅇㅁㅁㄴㅇㅁㄴㅇ
Here are some ideas to get you started:
asdasda
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...ㄴㅇㄹㅇㄴㄹㅇㄴ
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
