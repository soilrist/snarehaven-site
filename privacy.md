---
title: Snarehaven 개인정보처리방침 / Privacy Policy
permalink: /privacy/
---

# Snarehaven 개인정보처리방침 / Privacy Policy

## 한국어

**시행일:** 앱 스토어 출시일
**문의·삭제 요청:** snarehaven@gmail.com

Snarehaven(이하 "게임")은 계정 가입 없이 기기로 자동 로그인하는 게임입니다. 이름·이메일·전화번호 같은 개인 정보를 받지 않습니다. 이 방침은 게임이 다루는 데이터를 있는 그대로 적습니다.

### 1. 우리가 다루는 데이터

| 데이터 | 무엇인가 | 어디로 가는가 |
|---|---|---|
| 기기 식별자 | 기기마다 다르고 재부팅·재설치에도 유지되는 값. 사람 이름이 아닙니다. 로그인할 때 쓰입니다. | PlayFab(Microsoft) 로그인 요청 |
| 기기 식별자 (EOS) | Epic Online Services SDK 가 기기에서 직접 꺼내는 값. 게임은 빈 토큰만 넘깁니다. | Epic Online Services(Epic Games) 게스트 로그인 |
| PlayFab 계정 번호 | 로그인하면 받는 익명 계정 번호 | PlayFab 에 저장되고, 기기 안 캐시 파일에도 적힙니다 |
| EOS 계정 번호 | EOS 의 익명 계정 번호 | 같은 방에 있는 다른 플레이어에게 보입니다 |
| 인벤토리·스네어 코인 잔액 | 아이템 ID 와 개수, 가상 재화 잔액 | PlayFab 이 원본을 보관합니다 |
| 목장 상태 | 슬롯 번호, 동물 ID, 맡긴 시각, 재고 | PlayFab 플레이어 데이터 |
| 통신 상대 주소 | 4~8인 협동 플레이는 EOS 릴레이를 거칩니다. 참가자끼리 IP 주소를 직접 주고받지 않습니다. | Epic(릴레이) |
| 기기 안 저장 파일 | 인벤토리·코인·PlayFab 계정 번호·조회 시각을 담은 표시용 캐시. 밖으로 나가지 않습니다. | 기기 내부에만 |
| 분석 이벤트 | 게임에서 일어난 일의 이름과 칸: 잡은 동물 ID, 지역 ID, 목장 슬롯 번호, 바뀐 잔액, 새 계정 여부, 죽을 때 버려진 지급 대기 줄 수(개수만). 사람 이름·위치·기기 정보·자유 입력 글은 포함되지 않습니다. | PlayFab, 내 PlayFab 계정 번호에 붙어 쌓입니다 |

분석 이벤트 종류: `animal_killed` · `animal_capture_succeeded` · `animal_capture_failed` · `ranch_pet_register_requested` · `ranch_harvest_requested` · `gacha_pull_requested` · `currency_balance_changed` · `session_started` · `zone_travelled` · `player_died`

### 2. 받지 않는 것

이름·이메일·전화번호·생년월일, 채팅·음성, 광고 식별자·광고 SDK, 별도의 분석·크래시 리포트 SDK(분석 이벤트는 위 표대로 PlayFab 으로만 나갑니다), 위치·연락처·사진·마이크, 결제 정보(1.0 에는 유상 재화 판매가 없습니다).

### 3. 제3자 처리자

- **PlayFab (Microsoft)** — 위 계정·인벤토리·목장·분석 이벤트를 보관합니다. 방침: https://privacy.microsoft.com/privacystatement
- **Epic Online Services (Epic Games)** — 기기 식별자·EOS 계정 번호·세션 통신(릴레이). 방침: https://www.epicgames.com/site/privacypolicy

### 4. 보관과 삭제

- 데이터는 계정이 있는 동안 보관됩니다. 보관 기간: 계정을 삭제할 때까지
- **앱 안에서 직접 삭제:** 로비 `설정` → `계정 삭제` → 확인 두 번. 서버가 삭제를 확인해야 기기 연결과 기기 안 캐시가 지워집니다. 이 타이틀의 플레이어 계정(목장·인벤토리·재화·통계 등)이 지워지고, 같은 기기로 다시 들어오면 빈 새 계정이 만들어집니다.
- **시간이 걸리는 것:** PlayFab 의 상위(마스터) 계정과 이벤트 기록은 운영자가 따로 지웁니다. 삭제 요청이 기록되며, 처리 주기는 요청 후 30일 이내입니다.
- 앱을 쓸 수 없을 때는 snarehaven@gmail.com 으로 삭제를 요청할 수 있습니다.
- EOS 쪽에는 우리 개인 데이터를 두지 않습니다(익명 기기 번호뿐).

### 5. 아동

이 게임은 만 14세 미만(한국)·13세 미만(COPPA) 아동을 대상으로 하지 않습니다. 아동의 정보를 알고 수집하지 않으며, 알게 되면 삭제합니다.

### 6. 문의

snarehaven@gmail.com

---

## English

**Effective date:** the App Store release date
**Contact / deletion requests:** snarehaven@gmail.com

Snarehaven ("the Game") signs you in automatically with a device identifier. There is no sign-up screen, and the Game does not ask for your name, email, or phone number. This policy lists the data the Game handles as it is.

### 1. Data we handle

| Data | What it is | Where it goes |
|---|---|---|
| Device identifier | A value unique to the device that persists across reboots and reinstalls. It is not your name. Used to sign in. | PlayFab (Microsoft) sign-in request |
| Device identifier (EOS) | Read directly from the device by the Epic Online Services SDK. The Game passes only an empty token. | Epic Online Services (Epic Games) guest sign-in |
| PlayFab account ID | An anonymous account number returned at sign-in | Stored in PlayFab and in a cache file on the device |
| EOS account ID | An anonymous EOS account number | Visible to other players in the same room |
| Inventory and Snare Coin balance | Item IDs and counts, virtual currency balance | PlayFab holds the master copy |
| Ranch state | Slot number, animal ID, time placed, stock | PlayFab player data |
| Peer network address | 4–8 player co-op goes through an EOS relay. Players do not exchange IP addresses directly. | Epic (relay) |
| On-device save file | A display cache of inventory, coins, PlayFab account ID, and fetch time. It never leaves the device. | Device only |
| Analytics events | The name and fields of what happened in the game: captured animal ID, zone ID, ranch slot number, changed balance, whether the account is new, and the count of dropped pending-grant entries on death (a number only). No name, location, device information, or free-text input is included. | PlayFab, stored against your PlayFab account ID |

Analytics event types: `animal_killed` · `animal_capture_succeeded` · `animal_capture_failed` · `ranch_pet_register_requested` · `ranch_harvest_requested` · `gacha_pull_requested` · `currency_balance_changed` · `session_started` · `zone_travelled` · `player_died`

### 2. What we do not collect

Name, email, phone number, date of birth; chat or voice; advertising ID or ad SDKs; a separate analytics or crash-report SDK (analytics events go only to PlayFab as listed above); location, contacts, photos, microphone; payment information (version 1.0 sells no paid currency).

### 3. Third-party processors

- **PlayFab (Microsoft)** — stores the account, inventory, ranch, and analytics events above. Policy: https://privacy.microsoft.com/privacystatement
- **Epic Online Services (Epic Games)** — device identifier, EOS account ID, session traffic (relay). Policy: https://www.epicgames.com/site/privacypolicy

### 4. Retention and deletion

- Data is kept while the account exists. Retention period: until the account is deleted
- **Delete in the app:** Lobby `Settings` → `Delete account` → confirm twice. The device link and on-device cache are removed only after the server confirms deletion. The player account for this title (ranch, inventory, currency, statistics, etc.) is deleted; signing in again on the same device creates a new empty account.
- **What takes longer:** the PlayFab master account and event records are removed separately by the operator. A deletion request is logged; the request is processed within 30 days.
- If you cannot use the app, request deletion at snarehaven@gmail.com.
- We keep no personal data of ours in EOS (only an anonymous device ID).

### 5. Children

The Game is not directed at children under 14 (Korea) or under 13 (COPPA). We do not knowingly collect children's information and will delete it if we learn of it.

### 6. Contact

snarehaven@gmail.com
