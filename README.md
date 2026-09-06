# 김성민 (tolelom)

게임 클라이언트와 게임 서버, 프로그래밍 언어를 직접 만듭니다.
UE5 C++ 경영 시뮬레이션을 Steam 출시 준비 중이고, Go 게임 서버와 C++ 인터프리터를 밑바닥부터 구현했습니다.

포트폴리오: [tolelom.xyz](https://tolelom.xyz) · 알고리즘: [solved.ac/tolelom](https://solved.ac/tolelom)

## 대표 작업

### Claw Machine Shop Simulator
UE5 경영 시뮬레이션. 7인 팀 PM 겸 시스템 개발자로 C++ 소스 약 4.5만 줄에 팀 내 최다 기여.
세이브/로드, 36단계 경제 밸런스, 4개 언어 다국어 파이프라인, CI 잡 7종을 담당했습니다.
저장소는 팀 비공개.
[Steam 스토어](https://store.steampowered.com/app/4745630/Claw_Machine_Shop_Simulator/)

### One of the Plans
Photon Fusion 멀티플레이 보스레이드 게임. 6인 팀 팀장으로 Go 게임 서버와 런처를 단독 개발하고
Unity 클라이언트에 최다 기여했습니다. 방 상태 관리, HKDF 지갑 키 파생, 체인 노드 페일오버를 다뤘습니다.
[tolchain](https://github.com/tolelom/tolchain) (프라이빗 블록체인, 설계 주도 구현은 AI 협업)

### Neo-Slasher
모바일 2D 로그라이크. 8인 팀 프로그래밍 디렉터로 아키텍처를 주도해 스토어 출시했고(현재 서비스 종료),
이후 코드베이스를 단독으로 전면 리팩토링했습니다. IDamageSource 인터페이스 도입, BaseItem 추상화로
GameObject.Find 의존성 제거, Unity 6 마이그레이션.
[Neo-Slasher_Refactoring](https://github.com/Neo-Slasher/Neo-Slasher_Refactoring)

### Hongik
한글 키워드 프로그래밍 언어의 C++ 인터프리터. 파서 생성기 없이 토크나이저, 재귀 하강 파서,
AST 평가기, 메모리 관리를 단독 작성했습니다. 브라우저 플레이그라운드로 배포해 운영 중입니다.
[hong-ik](https://github.com/hongik2023graduationproject/hong-ik) · [hongik.tolelom.xyz](https://hongik.tolelom.xyz)

## 그 외 저장소

### 게임
- [Project-RA](https://github.com/kebap-studio/Project-RA): 로그라이크 액션
- [PocketBall](https://github.com/tolelom/PocketBall): 포켓볼 시뮬레이터

### 서버 / 백엔드
- [sion-backend](https://github.com/tolelom/sion-backend): AGV 실시간 관제 서버 (Go Fiber, WebSocket)
- [sion-frontend](https://github.com/tolelom/sion-frontend): 관제 대시보드 (React)
- [sion](https://github.com/tolelom/sion): 로봇 제어 (Python, A* 경로 탐색)
- [tolelog-backend](https://github.com/tolelom/tolelog-backend): 블로그 REST API (Go Fiber)
- [tolelog](https://github.com/tolelom/tolelog): 블로그 프론트엔드 (React, TypeScript)

### 언어 / 학습
- [dubong-language](https://github.com/tolelom/dubong-language): 언어 구현 습작
- [algorithm](https://github.com/tolelom/algorithm): 알고리즘 풀이
- [gymnasium](https://github.com/tolelom/gymnasium): 강화학습 커스텀 환경
- [battle_city_deep_learning](https://github.com/tolelom/battle_city_deep_learning): 배틀시티 강화학습
- [All_In_One_Infotainment_System](https://github.com/tolelom/All_In_One_Infotainment_System): 차량 인포테인먼트

## 기술

게임: Unreal Engine 5 (C++, Blueprint), Unity (C#), Photon Fusion
서버: Go (Fiber), WebSocket, JWT/OAuth2, MySQL, Redis
언어/시스템: C, C++, Python, TypeScript
인프라: Docker, Caddy, Traefik, Prometheus, Grafana, Loki

Mac Mini 두 대에 20개 이상 서비스를 셀프호스팅으로 배포하고 운영합니다.
