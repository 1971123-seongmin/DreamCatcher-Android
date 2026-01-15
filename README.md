## Dream Catcher
<p align="center">
 <img src="https://github.com/user-attachments/assets/b3c53445-c952-41ab-9080-f14a787c2a7a" alt="드림캡쳐"/>
</p>
<div align="center">
대전광역시, 카이스트 주관 SPARCS 과학 해커톤, <b>대전문화정보산업진흥원장상 수상</b> <br>
어린이들이 대전광역시를 여행하며 과학을 배울 수 있는 꿈 컨셉의 선택지형 스토리 게임 앱 (안드로이드 파트)
</div>

## 개요
대전 SPARCS 과학 해커톤에서 진행한 프로젝트로, 대전을 여행하며 특정위치에 도착하면 선택지형 게임으로 과학을 배울 수 있는 스토리 게임 앱입니다.
- 프로젝트 이름: Dream Catcher (대전 SPARCS 과학 해커톤)
- 프로젝트 기간: 2024.10.18 ~ 10.20 (2박 3일)
- 개발 엔진 및 언어: Android Studio, Kotlin
- 멤버: 김성민 외 기획,디자인 1명, 백엔드 2명

## 목차
  - [내용](#내용)
  - [화면](#화면)
  - [기술스택](#기술스택)
  - [실행영상](#실행영상)
  - [느낀점](#느낀점)
  - [저작권](#저작권)

## 내용
- 시작화면
- 로그인
    - 이름, 나이를 입력하고 로그인
- 지도 화면 (홈)
    - Naver Map, FusedLocationProvider를 결합하여 사용자의 현재 위치를 추적하여 퀘스트 마커를 표시한다.
    - 마커를 클릭하면 상단에서 다이얼로그가 뜨고 클릭하면 게임을 진행할 수 있다.
- 게임 화면
    - 적절한 선택지를 골라 게임을 이어나갈수 있고 게임을 완료하면 뱃지를 얻는다.
- 뱃지 / 뱃지 보관함
    - 게임을 완료하면 뱃지 보관함에 뱃지가 추가되고, 해당 뱃지를 클릭하면 뱃지 정보를 자세히 볼 수 있다.

## 화면
| 시작 화면 |             로그인             |              지도(홈)               |              게임 화면               |              뱃지 보관함               |
|:---:|:-----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| <img width="200" src="https://github.com/user-attachments/assets/a8ea89e8-eb9c-4328-854b-cd7401c848df"/> | <img width="200" src="https://github.com/user-attachments/assets/fbb35879-70e7-4185-834f-d6c49c760b98"/> | <img width="200" src="https://github.com/user-attachments/assets/3d5fbe06-3843-4122-acf5-58497e6203c3"/> | <img width="200" src="https://github.com/user-attachments/assets/e0c38934-55b0-4d99-9f15-2ee3a2a67493"/> | <img width="200" src="https://github.com/user-attachments/assets/a1f22017-dd16-4eb5-b085-dacd3b3d3fc2"/> |

## 기술스택
### **🤖** 안드로이드
| **Category** | **TechStack** |
| --- | --- |
| Language | Kotlin |
| UI | XML |
| Architecture | Repository Pattern, MVVM |
| DI | Hilt |
| Network | Retrofit, OkHttp |
| Asynchronous | Coroutine, Flow |
| Jetpack | Navigation |
| Image | Glide |
| Map | Naver Map SDK |

## 실행영상
<div align="center">
  <video src="https://github.com/user-attachments/assets/a2a5a3d1-df83-4b82-b6f4-618607e845d7" width="200" height="200" controls>
  </video>
</div>

## 느낀점
- **제한된 시간에서의 압박감**: 안드로이드 개발을 혼자 담당하며 기술적인 문제를 전부 스스로 해결해야 한다는 부담감이 컸습니다. 특히 초기에 Gradle 설정이 꼬여서 많은 시간을 써야했는데, 제한된 시간 안에 앱을 완성해야 하는 상황 속에서 문제를 하나씩 풀어가며 예기치 못한 문제를 해결하고 평정심을 가질 수 있는 경험을 했습니다.

- **실시간 위치 기반 서비스 적용**: Naver Map SDK를 활용해 사용자의 현재 위치에 따라 마커를 띄우고 상호작용하는 기능을 구현했습니다. 위치 권한 처리부터 실시간 데이터 동기화까지 이어지는 위치 기반 서비스의 기초적인 동작 흐름을 경험해 볼 수 있었습니다.

- **사용자 타겟 분석에 기반한 서비스 기획**: 기획 단계에서 과학 축제라는 행사 특성을 고려해 가족과 동반ㅎ 어린이를 핵심 타겟으로 설정했습니다. 이들의 흥미를 끌 수 있도록 선택지형 스토리 게임 형식을 주제로 해서, 실제 현장에서도 예상대로 많은 어린이들이 방문하는 것을 보며 타겟팅된 서비스가 실제 사용자 관심을 끌고 만족으로 이어지는 큰 경험을 했습니다. 

## 저작권
Copyright 2024. 전세원 All rights reserved.<br>
ⓒ 2024. 전세원 All rights reserved.<br>
(c) 2024. 전세원 All rights reserved.

