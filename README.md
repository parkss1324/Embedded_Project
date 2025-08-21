# Open_Whether_API를 활용한 LED 구름
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

## 💻 기술 스택 및 개발 환경
- **기술 스택** : C, Embedded, API
- **소프트웨어** : Arduino

## 📌 주요 기능
- 사용자의 API 키와 한국 지역, 대구 지역의 고유 값들을 받아옵니다.
  
<img width="752" height="96" alt="Image" src="https://github.com/user-attachments/assets/d67ace7e-a724-4d50-b0fa-3a4d4c045ae6" /><br><br>

- WIFI ID와 PASSWORD를 받아옵니다.
  
<img width="428" height="383" alt="Image" src="https://github.com/user-attachments/assets/dbf8dced-8cca-4300-b3ae-fb535bff2c1d" /><br><br>
  
- LED의 RED, GREEN, BLUE의 값들을 각각 하나씩 ON되게 배열로 구성합니다.

<img width="321" height="257" alt="Image" src="https://github.com/user-attachments/assets/90a72949-b6bb-4c7a-92ec-e3cf1f3c57b2" /><br><br>

- 15도 미만의 온도에서는 BLUE, 15도 이상 25도 이하의 온도에서 GREEN, 25도를 초과한 온도에서는 RED를 출력하는 조건문을 만듭니다.

<img width="343" height="321" alt="Image" src="https://github.com/user-attachments/assets/d68eee36-a53c-442b-88d4-a8517b6642a4" /><br><br>

  
- 결과를 확인합니다.
  
<img width="366" height="271" alt="Image" src="https://github.com/user-attachments/assets/34d4277f-0708-4ab3-b251-f17c83c8142e" />


## ✒️ API
- API 개념 및 장단점: [https://terms.naver.com/entry.naver?docId=1179553&cid=40942&categoryId=32837](https://www.hanl.tech/blog/api%EB%9E%80-api%EC%9D%98-%EC%A0%95%EC%9D%98%EC%99%80-%EC%A2%85%EB%A5%98-%EC%9E%A5%EB%8B%A8%EC%A0%90/)
