# Histour
## 프로젝트 소개
<div align="center">
<img src="https://github.com/HisTour-capstone04/HisTour-Frontend/blob/main/assets/icon.png" width="300" height="300" />
</div><br>

**HisTour는 ‘History’와 ‘Tour’를 결합한 이름으로, 유적지 탐방의 새로운 경험을 제공하는 모바일 애플리케이션입니다.**
<br>
<br>HisTour는 정보 부족과 접근성의 불편함으로 유적지에 관심이 있어도 쉽게 방문하지 못하는 문제를 해결하고, 더 많은 사람들이 유적지를 통해 역사와 문화를 경험할 수 있도록 돕고자 개발되었습니다. 사용자의 현재 위치를 기반으로 주변 유적지 정보를 탐색하고, 개인 맞춤형 유적지 추천, 길찾기, 챗봇 기능 및 근처 유적지 발견 시 푸시알림을 제공합니다. 
<br>
<br>2025년 1학기 중앙대학교 소프트웨어학부 캡스톤디자인(2)에서 진행한 프로젝트입니다.
<br>
<br>

## 기술 스택
**Frontend**:
<br>
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
<img src="https://img.shields.io/badge/react%20native-61DAFB?style=for-the-badge&logo=react&logoColor=black"> 
<br>
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/Expo-1C2024?style=for-the-badge&logo=Expo&logoColor=white"> 
<br>
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
<img src="https://img.shields.io/badge/css-663399?style=for-the-badge&logo=css&logoColor=white">
<br>

**Backend** : 
<br>
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<br>
<img src="https://img.shields.io/badge/postgresql-4479A1?style=for-the-badge&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/redis-FF4438?style=for-the-badge&logo=redis&logoColor=white">
<br>
<img src="https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"> 
<img src="https://img.shields.io/badge/amazonrds-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white"> 
<br>
<img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/githubactions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">

## 기능 소개
### 데모 영상
<div align="center">
    
[![image](https://github.com/user-attachments/assets/a3defa63-0724-4a01-9734-cb86a4494c1d)](https://youtu.be/CoeC7rlyzjk?si=LPyyvEb-bvYpmj6N)
앱의 주요 기능을 설명 및 시연하는 데모 영상입니다. 이미지 클릭 시 영상 재생 페이지로 이동합니다. </div>
<br>

### 🔐 로그인/회원가입
- 이메일과 비밀번호를 입력하여 간편하게 로그인할 수 있습니다.
- 신규 사용자는 이름, 이메일, 비밀번호를 입력하여 회원가입이 가능합니다.
- 잘못된 정보 입력 시 재입력을 안내합니다.
<br>

### 🏠 홈 화면
> 구성 : 검색창, 슬라이더 바, 지도, 슬라이드 패널, 아코디언 버튼 (챗봇/지도 중심 재설정/지도 상 유적지 조회 버튼)
- 유적지를 검색할 수 있는 검색창이 제공됩니다.
- 유적지를 조회할 반경을 설정할 수 있는 슬라이더 바가 있습니다. 반경은 최소 0m부터 최대 2km까지 설정할 수 있습니다.
- 사용자의 위치 마커, 설정한 반경 원, 그리고 주변 유적지 마커들이 지도 상에 표시됩니다. 동일한 위치에 여러 유적지가 있을 경우 하나의 마커로 그룹화됩니다.
- 특정 유적지의 마커를 클릭하면, 해당 유적지의 정보가 담긴 슬라이드 패널이 화면 하단에서 위로 올라오며 제공됩니다.
- 챗봇 화면 이동 버튼, 지도 중심을 현재 사용자 위치로 재설정하는 버튼, 현재 지도 상 모든 유적지를 조회하는 버튼이 제공되며, 이 세 가지 버튼은 아코디언 버튼으로 관리됩니다.
<br>

### 📍 주변 정보
- 사용자의 주변에 있는 유적지에 대한 상세 정보(이름, 거리, 상세 주소, 설명, 사진)를 제공합니다.
- 북마크, 장바구니, 출발지/도착지 설정, 챗봇 버튼을 통해 다양한 기능을 이용할 수 있습니다.
<br>

### 🗺️ 길찾기
- 자동차/대중교통/도보 길찾기를 지원합니다.
- 출발지, 목적지와 최대 5개의 경유지를 설정할 수 있습니다.
- 경로를 설정하여 길찾기 모드에 진입 시 지도 상에 출발지/경유지/목적지 마커와 경로가 표시됩니다.
- 드래그하여 경로 상 유적지들의 순서를 변경하고, 제거 버튼을 눌러 필요 없는 경유지를 삭제할 수 있습니다.
<br>

### ⭐ 북마크
- 북마크한 유적지에 대한 상세 정보(이름, 거리, 상세 주소, 설명, 사진)를 제공합니다.
- 북마크한 유적지는 지도 상에 별 모양 마커로 항상 표시됩니다.
<br>

### 👤 마이 페이지
- 사용자의 위치, 북마크, 날씨 등을 고려한 맞춤형 유적지 추천을 제공합니다.
- 추천 이유를 함께 제공하여 신뢰도 높은 추천 경험을 제공합니다.
<br>

### 🔍 검색
- 원하는 유적지를 검색할 수 있으며, 최근 검색어 15개까지 저장됩니다.
- 검색 결과는 지도에 바로 표시되고, 슬라이드 패널로 정보를 확인할 수 있습니다.
<br>

### 💬 챗봇
- 유적지에 대한 궁금증을 챗봇을 통해 바로 해결할 수 있습니다.
- 답변은 음성(TTS)으로도 들을 수 있으며, 자동 음성 설정이 가능합니다.
- 꼬리질문 버튼으로 추가 질문, 목적지 설정, 장바구니 추가 기능을 손쉽게 이용할 수 있습니다.
<br>

### 🔔 푸시 알림
- 5분마다 사용자의 위치를 기반으로 새로운 유적지 발견 시 푸시 알림을 제공합니다.
- 가장 가까운 유적지와 새로 발견된 유적지 개수를 한 번에 확인할 수 있습니다.
<br>

## 파일 디렉토리 구조
- Frontend
```
Histour/
├── assets/                   
│   ├── images/
│   │   └── map/              # 지도 관련 마커 이미지들
│   ├── adaptive-icon.png     # 로딩 화면 아이콘 (Android)
│   ├── favicon.png           # 파비콘
│   ├── icon.png              # 앱 아이콘
│   ├── splash-icon.png       # 로딩 화면 아이콘 (iOS)
│   └── heritage.svg          # 유적지 아이콘
├── components/               
│   ├── MapWebView.js         # 웹뷰 기반 지도
│   ├── RecenterMapButton.js  # 지도 중심 재설정 버튼
│   ├── HeritageFindButton.js # 현재 지도 내 유적지 조회 버튼
│   ├── ChatbotButton.js      # 챗봇 버튼
│   └── AccordionButton.js    # 아코디언 버튼
├── screens/                  
│   ├── AuthScreen.js          # 로그인/회원가입 화면
│   ├── SearchScreen.js        # 검색 화면
│   ├── ChatbotScreen.js       # 챗봇 화면
│   ├── ChatbotConfigScreen.js # 챗봇 설정 화면
│   ├── ConfigScreen.js        # 설정 화면
│   └── Home/                       
│       ├── HomeScreen.js           # 홈 화면
│       ├── HeritageDetailPanel.js  # 유적지 상세 슬라이드 패널
│       ├── SlidePanel.js           # 슬라이드 패널
│       ├── SearchBar.js            # 검색 바
│       ├── RangeSlider.js          # 범위 슬라이더
│       ├── FooterTabBar.js         # 하단 탭 바
│       └── panels/                 # 슬라이드 패널 상 표시될 컨텐츠들
│           ├── BookmarkPanel.js    # 북마크 탭
│           ├── NearbyPanel.js      # 주변 정보 탭
│           ├── MyPagePanel.js      # 마이 페이지 탭
│           └── DirectionsPanel.js  # 길찾기 탭
├── contexts/                 
│   ├── AuthContext.js                 # 인증 상태 관리
│   ├── BookmarkContext.js             # 북마크 상태 관리
│   ├── HeritageContext.js             # 유적지 데이터 관리
│   ├── HeritageNotificationContext.js # 푸시 알림 관리
│   ├── RouteContext.js                # 길찾기 경로 상태 관리
│   ├── RouteModeContext.js            # 길찾기 모드 관리
│   ├── UserLocationContext.js         # 사용자 위치 관리
│   └── ViaContext.js                  # 장바구니 유적지 관리
├── navigation/               
│   └── MainNavigator.js      # 메인 네비게이터
├── theme/                    
│   └── colors.js             # 테마 색상 정의
└── hooks/                    
    └── useDebouncedValue.js  # 디바운싱 용 커스텀 훅
```
- Backend
```
src/
├── main/
│   ├── java/
│   │   └── com/capstone/HisTour/
│   │       ├── domain/                     # 핵심 비즈니스 로직 및 엔티티
│   │       │   ├── alarm/                  # 알림 관련 도메인
│   │       │   │   ├── controller/         # 알림 API 요청 처리
│   │       │   │   ├── domain/             # 알림 엔티티
│   │       │   │   ├── dto/                # 알림 데이터 전송 객체
│   │       │   │   ├── repository/         # 알림 데이터 접근 계층
│   │       │   │   └── service/            # 알림 비즈니스 로직
│   │       │   ├── api/                    # 외부 API 연동 또는 공통 API
│   │       │   │   ├── controller/
│   │       │   │   └── service/
│   │       │   ├── apiPayload/             # API 응답 형식 및 예외 처리 관련
│   │       │   │   ├── code/               # HTTP 응답 코드 및 사용자 정의 에러 코드
│   │       │   │   ├── exception/          # 사용자 정의 예외
│   │       │   │   ├── status/             # API 응답 상태 정보
│   │       │   │   └── DefaultResponse.java# 공통 응답 DTO
│   │       │   ├── bookmark/               # 북마크 관련 도메인
│   │       │   │   ├── controller/
│   │       │   │   ├── domain/
│   │       │   │   ├── dto/
│   │       │   │   ├── repository/
│   │       │   │   └── service/
│   │       │   ├── chatbot/                # 챗봇 관련 도메인
│   │       │   │   ├── controller/
│   │       │   │   ├── domain/
│   │       │   │   ├── dto/
│   │       │   │   ├── repository/
│   │       │   │   └── service/
│   │       │   ├── heritage/               # 유적지 관련 도메인
│   │       │   │   ├── controller/
│   │       │   │   ├── domain/
│   │       │   │   ├── dto/
│   │       │   │   ├── repository/
│   │       │   │   └── service/
│   │       │   ├── member/                 # 회원 관련 도메인
│   │       │   │   ├── controller/
│   │       │   │   ├── domain/
│   │       │   │   ├── dto/
│   │       │   │   ├── repository/
│   │       │   │   └── service/
│   │       │   ├── push_token/             # 푸시 알림 토큰 관리
│   │       │   ├── refresh_token/          # JWT 리프레시 토큰 관리
│   │       │   ├── region/                 # 지역 관련 도메인
│   │       │   │   ├── domain/
│   │       │   │   ├── dto/
│   │       │   │   └── service/
│   │       │   └── visited/                # 방문 기록 관련 도메인
│   │       │       ├── controller/
│   │       │       ├── domain/
│   │       │       ├── dto/
│   │       │       ├── repository/
│   │       │       └── service/
│   │       ├── global/                     # 전역 설정 및 공통 유틸리티
│   │       │   ├── annotation/             # 커스텀 어노테이션
│   │       │   ├── aop/                    # AOP (Aspect-Oriented Programming)
│   │       │   ├── auth_jwt/               # JWT 인증 관련
│   │       │   ├── config/                 # 전역 설정 및 빈 설정
│   │       │   ├── error/                  # 전역 에러 처리
│   │       │   └── BaseTimeEntity.java     # 공통 BaseTimeEntity
│   │       └── HisTourApplication.java     # 메인 애플리케이션 클래스
│   └── resources/                  # 자원 파일
│       ├── static/                 # 정적 웹 리소스 (선택 사항)
│       ├── templates/              # 템플릿 파일 (선택 사항)
│       └── application.yml         # Spring Boot 설정 파일
└── test/
├── java/
│   └── com/capstone/HisTour/
│       ├── heritage/             # 유적지 테스트 코드
│       ├── member/               # 회원 테스트 코드
│       └── HisTourApplicationTests.java # 통합 테스트
└── resources/
└── application-test.yml    # 테스트 환경 설정 파일
```
