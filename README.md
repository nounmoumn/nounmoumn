<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e293b,100:2563eb&height=160&section=header&text=Sungjin%20Lim&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Korea%20University%20-%20AI%20and%20Robotics&descAlignY=58&descSize=16" width="100%" />

</div>

## 임성진 · Sungjin Lim

고려대학교 정보대학 인공지능학과 · 2학년

웹 서비스, Rust 데스크톱 에이전트, C++ 실시간 오디오, 로봇 팔 제어까지 여러 층위를 직접 만들어 보고 있습니다.


<div align="center">

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)

</div>

---

### 프로젝트

#### IDA 입시연구소 · 웹 서비스
> 2026.05 – 07 · **커밋 44개 중 36개 담당** · [**서비스 ↗**](https://www.acon.io.kr/susi-placement)
> `TypeScript` `HTML/CSS` `Python` `Docker`

입시 학원의 실서비스 웹사이트를 5주간 개발해 Vercel에 배포했습니다. 프론트엔드, 백엔드, 배포 인프라, AI 기능, 데이터 분석 초안까지 전 영역을 혼자 설계·구현했습니다. 나머지 팀원 커밋은 기존 학원 웹사이트와의 호환성 조정과 자잘한 버그 수정입니다.

---

#### [CATchME](https://github.com/nounmoumn/catchme-cat-map) · 3D 지도 고양이 도감
> 2026 여름 · 2인 팀 · **커밋 100** · [**데모 ↗**](https://catchme-rosy.vercel.app)
> `JavaScript` `Three.js` `OAuth` `Vercel`

캠퍼스에서 만난 고양이를 사진과 위치로 기록해 나만의 도감을 채우는 3D 지도 웹 서비스입니다.
**백엔드와 3D 모델링**을 맡아 기획부터 배포까지 마무리했습니다.

---

#### [SMIM 2.0](https://github.com/nounmoumn/smim-diary) · AI 그림일기 앱
> 2026 상반기 · **커밋 18** · [**데모 ↗**](https://smim-4fc74.web.app)
> `Flutter` `FastAPI` `PostgreSQL` `Cloud Run` `Gemma 3 (온디바이스)`

하루의 순간을 조각으로 모으면 사진의 GPS로 지도 일기를 그리고, AI가 그날의 조각을 분석해 수채화·픽셀아트 그림일기를 만들어 줍니다.
**온디바이스 모델과 이미지 생성 API를 실제 서비스에 통합**하고 클라우드에 배포했습니다.

---

#### [Do](https://github.com/nounmoumn/do-platform) · 고립 회복 플랫폼
> 2026 상반기 · GDGoC 해커톤 · **커밋 21** · [**데모 ↗**](https://team14-gdg.vercel.app)
> `Python` `AI`

외로움과 사회적 고립을 겪는 사람을 **실제 인간관계로 이어 주는 것**을 목표로 한 플랫폼입니다.
챗봇에 대한 정서적 의존을 늘리는 기존 AI 컴패니언 모델에 의도적으로 반대하는 설계를 택했습니다.
감정 안정 → 동기 회복 → 안전한 대인 교류 → 실제 사회 복귀의 단계를 설계했습니다.

---

#### [나작교](https://github.com/nounmoumn/inthon-7-backend) · 실시간 강의 Q&A 지원 시스템
> 2025 · INTHON 해커톤 · 2인 팀 · **커밋 13**
> `Django` `WebSocket` `Google Generative AI`

교수와 학생 간 실시간 상호작용을 돕는 강의 지원 서비스입니다. 학생들이 "이해했어요/어려워요"로 이해도를 즉시 표현하면 웹소켓으로 교수에게 전달되고, 질문은 Google Generative AI가 명료하게 다듬어 줍니다.
**Django 백엔드**를 담당했습니다.

---

#### [MouseKeeper](https://github.com/nounmoumn/mousekeeper) · 자연어 파일 관리 에이전트
> 2026 여름 · 2인 팀 · **커밋 97**
> `Rust` `SQLite` `WebSocket` `Android`

자연어로 파일을 찾고 정리하는 로컬 우선 에이전트입니다. **Rust 데스크톱 엔진 전체**를 맡았습니다.

- 조회는 자동 수행, 변경은 반드시 사용자 승인 후 실행
- symlink · junction · Windows reparse point를 이용한 관리 경로 이탈 차단
- 쓰기 전 저널 기록으로 비정상 종료 후 복구와 undo 보장
- watcher · reconcile · SQLite 인덱스

---

#### [Gitaru](https://github.com/nounmoumn/gitaru) · 실시간 기타-보컬 앱
> 2026 여름 · 2인 팀 · **커밋 47**
> `C++` `JUCE` `WORLD` `SoundTouch`

기타를 치면 보컬이 따라 나오고, 내가 부르면 기타 음정에 맞춰 목소리를 실시간 보정해 주는 데스크톱 앱입니다.
Dannenberg(1984)와 Dixon(2005)의 스코어 팔로잉 논문을 읽고 온셋 검출 · 크로마 기반 위치 추적 · 피치 시프팅을 구현했습니다.
체감 지연 **150ms** 목표로 구간별 지연 예산을 나눠 관리하고, 피치 시프터 3종을 동일 녹음으로 A/B 비교해 근거를 남긴 뒤 채택했습니다.

---

#### [PRECOG](https://github.com/nounmoumn/precog-game) · 미래 예측 액션 게임
> 2026 여름 · 4인 팀 · **커밋 61**
> `C#` `Unity`

전투의 현재 상태를 복제해 여러 미래를 시뮬레이션한 뒤 세 가지 돌파 경로를 제시하는 1인칭 액션 게임입니다.
예측과 실제 플레이가 다른 규칙을 쓰면 예측이 거짓이 되므로, 라이브 게임 · 후보 탐색 · 최종 재실행이 **모두 동일한 결정론적 시뮬레이션 함수**를 호출하도록 설계했습니다.

---

### 그 외

- **KAIST 몰입캠프 2026 여름** — 대학생 대상 4주 집중 개발 캠프. 웹 / Rust / Unity / C++ 네 프로젝트 전 과정을 완주했습니다.
- **AWS 자격 수료** — Building Agentic AI with Amazon Bedrock AgentCore(480분), AWS Technical Essentials
- **L-ZERO 학회 RTL 트랙** — 반도체 설계 학회의 디지털 회로(RTL) 스터디. Chisel과 Rocket-chip으로 RISC-V 코어 구조를 분석합니다.
- **로보틱스 스터디** — OpenManipulator-X 로봇 팔을 PyBullet으로 시뮬레이션하고, 펜 끝 좌표로 관절각을 구하는 해석적 역기구학을 직접 유도·구현했습니다.
- **[고려대 운영체제 과제](https://github.com/nounmoumn/korea-os-assignments)** — 수업 과제로 C 스케줄러와 시스템 콜을 직접 구현했습니다.
- **[AWS × 강원대·고려대 Agentic AI 심화 몰입캠프](https://github.com/nxtcloud-edu/2026_KNUxKU_summer_camp_team01)** — 도시와 날짜만 정하면 AI 에이전트가 일정을 짜 주는 여행 플래너(JustGO). 프론트엔드-에이전트 간 SSE 스트리밍 계약 설계에 참여했습니다.

---

### 지금 하는 것

- 스코어 팔로잉 구현 정리 및 Dixon 논문 실험 재현 — 감으로 맞췄던 파라미터를 근거를 대고 다시 잡는 중
- OpenManipulator-X 실기체로 펜 궤적 과제 마무리
- 공학수학 수강 중 / 다음 학기 신호및시스템 · 디지털신호처리 예정

<div align="center">

![Profile views](https://komarev.com/ghpvc/?username=nounmoumn&color=2563eb&style=flat-square&label=Views)

</div>
