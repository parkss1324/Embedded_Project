# Open_Whether_API
Whether API의 open source를 활용하여 대구 지역의 온도값을 구현한 소스 코드입니다.  

## 👨‍🏫 프로젝트 소개
30분마다 기온을 파악, 온도 변화에 따라 내부 LED의 색이 변하는 구름으로 보다 직관적이고, 아무 곳에서나 배치가 가능할 정도로 가볍습니다. 

## ⏲️ 개발 기간 
- 2021.04 ~ 2021.05
- 계획 수립
- 필요 부품 구입
- WIFI 기능 구현 및 확인
- API 기능 구현 및 확인
- 기온에 따른 LED 색 변화 소스코드 개발
- 포트폴리오 제작
  
## 🧑‍🤝‍🧑 개발 인원 : 1
- **박성수** : 전체 프로젝트 기획 및 개발

## 💻 개발 환경 및 기술 스택
- **소프트웨어** : Arduino
- **기술 스택** : C, Embedded, API

## 📌 주요 기능
- 사용자 고유의 API 키와 한국 지역, 대구 지역의 특정 값들을 받아온다.
- WIFI ID와 PASSWORD를 받아온다.
- LED의 RED, GREEN, BLUE의 값들을 각각 하나씩 ON되게 배열로 구성한다.
- 15도 미만의 온도에서는 BLUE, 15도 이상 25도 이하의 온도에서 GREEN, 25도를 초과한 온도에서는 RED를 출력하는 조건문을 만든다.
- 딜레이를 써서 30분마다 기록이 갱신되게 만든다.

## ✒️ API
- API 개념 및 장단점: [https://terms.naver.com/entry.naver?docId=1179553&cid=40942&categoryId=32837](https://www.hanl.tech/blog/api%EB%9E%80-api%EC%9D%98-%EC%A0%95%EC%9D%98%EC%99%80-%EC%A2%85%EB%A5%98-%EC%9E%A5%EB%8B%A8%EC%A0%90/)
