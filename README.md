# m-SIGNAL · Materials Signal Intelligence

SK hynix 소재전략팀 전용 인텔리전스 시스템 — 소재 시장 동향 · 기술 변곡점 · BP 활동을 자동 수집 · 분석 · 보고서화

**🌐 Live**: https://piko9388.github.io/mSIGNAL/

---

## 구조

```
/
├── index.html              # 랜딩 · 아카이브 허브
├── overview.html           # System Overview (별첨)
├── weekly/
│   ├── WW17.html           # 주간 보고서 (WW별 1파일)
│   └── WW18.html           # (차주 발행 예정)
├── assets/
│   └── logo.png            # SK hynix 로고
└── templates/
    ├── daily-signal.html   # Daily Signal 이메일 템플릿
    └── key-signal.html     # Key Signal 공유 카드
```

## 주요 산출물

| 산출물 | 발송 주기 | 설명 |
|---|---|---|
| **Daily Signal** | 매일 08:00 KST | 전일 신규 Signal 요약 이메일 |
| **Weekly Report** | 매주 금 10:00 KST | Tier별 종합 10p 보고서 |
| **Key Signal** | Signal 발생 즉시 | 고영향 Signal 단건 공유 카드 |
| **BP Deep Dive** | 요청 시 48h 내 | 특정 BP 연간 종합 분석 |

## 배포 방법

### GitHub Pages 설정
1. Repository `Settings` → `Pages`
2. `Source`: `Deploy from a branch`
3. `Branch`: `main` / `root`
4. Save → `https://piko9388.github.io/mSIGNAL/`에서 자동 배포

### 주차별 보고서 추가
1. `weekly/WW{NN}.html` 생성 (이전 주 파일 복사 후 내용 교체)
2. `index.html`의 Archive 섹션에 카드 한 장 추가
3. `git commit -m "WW18 발행"` → `git push`

## 로컬 미리보기

```bash
# Python 간이 서버
python3 -m http.server 8080
# http://localhost:8080 접속
```

## 신뢰도 배지

- 🟢 **공식** — 기업 IR · 정부 발표 · 보도자료
- 🟠 **업계** — 전문 매체 다수 보도
- 🔴 **추정** — 단일 소스 · 정황 근거

## 문의

**이정훈 TL**
- 📱 010-3376-7923
- ✉ junghoon12.lee@sk.com

---

*m-SIGNAL v1.8.7 · Materials Signal Intelligence · SK hynix 소재전략 · 내부용 · 무단 외부 공유 금지*
