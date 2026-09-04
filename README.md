## 임성진 · Sungjin Lim

고려대학교 정보대학 인공지능학과 · 2학년

웹 서비스, Rust 데스크톱 에이전트, C++ 실시간 오디오, 로봇 팔 제어까지 여러 층위를 직접 만들어 보고 있습니다.
넓게 다녀 본 덕분에 이것들이 결국 **관측하고, 상태를 추정하고, 정해진 시간 안에 응답하는 같은 문제**라는 걸 알게 됐고, 지금은 그 자리를 더 파고 있습니다.

`C` `C++` `Rust` `Python` `TypeScript` `Dart` `C#`

---

### 프로젝트

#### IDA 입시연구소 · 웹 서비스
> 2026.05 – 07 · 3인 팀 · **커밋 44개 중 36개 담당 (팀 내 최다)** · [**서비스 ↗**](https://idacode.vercel.app)
> `TypeScript` `HTML/CSS` `Python` `Docker`

입시 학원의 실서비스 웹사이트를 5주간 개발해 Vercel에 배포했습니다. 프론트엔드 구현과 컨테이너 기반 배포 환경 구성을 맡았습니다.


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

- **KAIST 몰입캠프 2026 여름** — 4주 과정 전체 수료 (웹 / Rust / Unity / C++)
- **AWS** — Building Agentic AI with Amazon Bedrock AgentCore, AWS Technical Essentials 수료
- **L-ZERO 학회 RTL 트랙** — Chisel · Rocket-chip 기반 RISC-V 코어 스터디
- **로보틱스 스터디** — OpenManipulator-X, PyBullet 시뮬레이션과 해석적 역기구학
- **[운영체제 과제](https://github.com/nounmoumn/korea-os-assignments)** — C
- **[INTHON 2025](https://github.com/nounmoumn/inthon-7-backend)** — 해커톤 백엔드
- **[AWS × 강원대·고려대 Agentic AI 심화 몰입캠프](https://github.com/nxtcloud-edu/2026_KNUxKU_summer_camp_team01)** — AI 여행 플래너(JustGO), 프론트-에이전트 계약(SSE 스트리밍) 설계 참여

---

### 지금 하는 것

- 스코어 팔로잉 구현 정리 및 Dixon 논문 실험 재현 — 감으로 맞췄던 파라미터를 근거를 대고 다시 잡는 중
- OpenManipulator-X 실기체로 펜 궤적 과제 마무리
- 공학수학 수강 중 / 다음 학기 신호및시스템 · 디지털신호처리 예정
