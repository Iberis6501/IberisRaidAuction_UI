# IberisRaidAuction

WoW 공격대 GDKP 골드 분배 장부 애드온. 직관적 단일 창 + 인라인 편집 + 자동 전리품 캡처 + 거래 자동 등록 + 정산 보고서.

대상 클라이언트: Anniversary (1.15.x) / TBC / Wrath / Mists / Mainline.

## 라이센스

Apache License 2.0. 상세 조항은 [`LICENSE`](LICENSE) 참고.

## 사용법

```
/ira          장부 창 열기/닫기
/ira new      새 장부 시작
/ira help     전체 명령 목록
```

상세 명령은 인게임 `/ira help` 또는 옵션 패널 참고.

## 작업 내역 / Changelog

### v0.2 (2026-05-13)
- 코드 베이스 재구성
- namespace / 슬래시 (/ira) / SavedVariables (IberisRaidAuctionGlobalConfig, IberisRaidAuctionDatabase) rebrand
- 파일 prefix `IRA*` 적용
- LICENSE Apache 2.0 추가

### v0.1 (이전)
- 자체 골격 (단일 위젯/탭 분리 장부) — v0.2 에서 폐기
