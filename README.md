# FirstEscape

Unreal Engine 5의 기능과 Blueprint를 배우면서 제작하는  
**1인칭 탈출 게임 프로젝트**입니다.

작은 기능을 하나씩 직접 구현하면서 Unreal Engine의 기본 구조와
게임 제작 과정을 익히는 것을 목표로 합니다.

---

## 🎮 Game Concept

플레이어가 공간을 탐색하며 열쇠와 아이템을 찾고,
잠긴 문을 열어 최종적으로 탈출하는 간단한 1인칭 게임입니다.

---

# 📌 Development Progress

## Phase 1 — Basic Interaction ✅

Unreal Engine의 기본적인 상호작용 시스템을 구현합니다.

- [x] First Person 프로젝트 구성
- [x] 테스트용 맵 제작
- [x] Enhanced Input 설정
- [x] `IA_Interact` 생성
- [x] E키 상호작용
- [x] 문 열기 / 닫기
- [x] 상호작용 거리 감지
- [x] 범위 밖에서는 문 조작 불가능

---

## Phase 2 — Key & Locked Door System ✅

열쇠를 획득하고 잠긴 문을 해제하는 시스템을 구현합니다.

- [x] `BP_Key` 제작
- [x] 열쇠 Interaction Box 추가
- [x] 열쇠 접근 감지
- [x] `IA_Pickup` 생성
- [x] F키로 열쇠 획득
- [x] E키와 F키 상호작용 분리
- [x] `HasKey` 상태 저장
- [x] `IsLocked` 문 상태 추가
- [x] 일반 문 / 잠긴 문 구분
- [x] 열쇠가 없으면 잠긴 문 차단
- [x] 잠긴 상태 안내 메시지
- [x] 열쇠 보유 여부 확인
- [x] 열쇠 보유 시 문 잠금 해제
- [x] 잠금 해제 후 문 열기 / 닫기

### Interaction

| Key | Action |
| --- | --- |
| `E` | Door Interaction |
| `F` | Item Pickup |

---

## Phase 3 — Interaction UI 🚧

플레이어가 상호작용 가능한 대상을 쉽게 확인할 수 있도록
화면에 안내 UI를 표시합니다.

- [x] `UI` 폴더 생성
- [x] `WBP_Interaction` 생성
- [x] Canvas Panel 구성
- [x] `InteractionText` 추가
- [x] InteractionText 화면 하단 중앙 배치
- [x] 문 접근 시 `E - 문 열기` 표시
- [ ] 열쇠 접근 시 `F - 열쇠 줍기` 표시
- [ ] 상호작용 범위를 벗어나면 UI 숨기기
- [ ] 상황에 따라 안내 문구 변경

---

## Phase 4 — Key / Inventory UI ⬜

획득한 아이템을 플레이어가 확인할 수 있도록 UI를 구현합니다.

- [ ] 열쇠 보유 UI
- [ ] 열쇠 아이콘 표시
- [ ] `HasKey`와 UI 연결
- [ ] 간단한 인벤토리 구조

---

## Phase 5 — Player UI & Items ⬜

게임 플레이에 필요한 추가 시스템을 구현합니다.

- [ ] 체력 시스템
- [ ] 체력바 UI
- [ ] 1인칭 아이템 표시
- [ ] 손전등 또는 사용 가능한 아이템

---

## Phase 6 — Level Design ⬜

테스트용 공간을 실제 플레이 가능한 탈출 맵으로 확장합니다.

- [ ] 실제 플레이용 맵 제작
- [ ] 방 / 복도 구조 설계
- [ ] 열쇠 및 아이템 배치
- [ ] 잠긴 문 배치
- [ ] 탐색 동선 구성
- [ ] 탈출 지점 제작

---

## Phase 7 — Game Flow ⬜

게임의 시작부터 클리어까지 전체 흐름을 완성합니다.

- [ ] 게임 시작
- [ ] 탐색
- [ ] 아이템 획득
- [ ] 잠긴 구역 해제
- [ ] 탈출 조건
- [ ] 게임 클리어
- [ ] 재시작 기능

---

## Phase 8 — Polish ⬜

게임의 완성도를 높이는 작업을 진행합니다.

- [ ] 조명 개선
- [ ] 환경 사운드
- [ ] 문 / 아이템 효과음
- [ ] UI 디자인 개선
- [ ] 맵 디테일 추가
- [ ] 플레이 테스트
- [ ] 버그 수정

---

## Phase 9 — Build & Release ⬜

완성된 프로젝트를 실제 실행 가능한 게임으로 빌드합니다.

- [ ] Windows Build
- [ ] 최종 플레이 테스트
- [ ] 플레이 영상 제작
- [ ] README 최종 정리
- [ ] 프로젝트 스크린샷 추가

---

# 🛠 Tech Stack

- Unreal Engine 5
- Blueprint
- Enhanced Input
- UMG
- Git
- GitHub

---

# 🎯 Project Goal

이 프로젝트의 목표는 단순히 게임을 완성하는 것뿐만 아니라,

- Unreal Engine의 기본 구조 이해
- Blueprint를 이용한 게임 로직 구현
- 캐릭터와 Actor 사이의 데이터 전달
- Collision 기반 상호작용 구현
- UI 시스템 학습
- 게임의 시작부터 클리어까지 전체 제작 과정 경험
- Git / GitHub를 이용한 프로젝트 관리

를 직접 경험하는 것입니다.

---

# 📚 Current Status

**Phase 2 완료 / Phase 3 진행 중**

현재 문 상호작용, 열쇠 획득, 잠긴 문 시스템까지 구현했으며  
`WBP_Interaction`을 이용한 상호작용 UI를 제작하고 있습니다.

다음 작업:

> **Phase 3 — InteractionText 화면 하단 중앙 배치**
