# 측정 툴킷 (Brand Lift·MMM·MTA·Geo Lift·Aided Awareness·NPS)

L5 MEASUREMENT의 도구 가이드. 측정 3축(Brand·Activation·Long-term) 분리 원칙 (절대규칙 7).

## 도구별 비교

| 도구 | 측정 대상 | 강점 | 한계 | 한국 가용 | 비용 |
|------|---------|------|------|:-:|:-:|
| Brand Lift Study | Awareness·Consideration·Intent | 인과성·실험설계 | 단일 매체·단일 캠페인 | ✓ | $$ |
| MMM (Marketing Mix Modeling) | 채널별 기여도·장기 효과 | 멀티채널·offline 포함 | 6개월+ 데이터·모델링 | ✓ Robyn(Meta) | $$$ |
| MTA (Multi-Touch Attribution) | 여정·터치포인트 | 실시간 | iOS14.5 ATT 한계 | ⚠ | $$ |
| Geo Lift Test | Incrementality | 실제 시장 | 지역 분할 필요·2-4주 | ✓ | $$ |
| Aided/Unaided Awareness | 상기도 | 표준화·벤치마크 | 패널 비용·표본 500+ | ✓ DMC·닐슨·칸타 | $$ |
| NPS | 브랜드 충성·추천의도 | 단순·산업 비교 가능 | 산업별 벤치마크 상이 | ✓ | $ |
| Mental Availability (CEPs) | Byron Sharp 측정 | 본질적 | 방법론 표준 미정착 | ⚠ | $$$ |

## 측정 도구 선택 가이드

### Brand Lift Study
- **언제:** 단일 캠페인 효과 검증 (단일 매체)
- **방법:** Google·Meta·TikTok 제공 — 노출군 vs 비노출군 설문
- **벤치마크:** Awareness Lift 5-15%·Consideration 3-10%
- **표본:** 통계 유의성 위해 매체 권장 노출량 충족 필요

### MMM
- **언제:** 멀티채널 캠페인·연간·예산 배분 의사결정
- **방법:** 회귀·Bayesian 모델 (Meta Robyn·Google LMM·자체 모델링)
- **데이터:** 주간 단위 · 6개월+ · 30K+ 데이터포인트
- **출력:** 채널별 ROI·포화점·증분 매출

### MTA
- **언제:** 디지털 여정 추적·실시간 최적화
- **모델:** Last-click·First-click·Linear·Time-decay·Position-based·Data-driven (GA4·Markov)
- **한계:** iOS14.5 ATT (2021.4) 이후 상당 부분 데이터 손실
- **권장:** Last-click 단독 ✗·MMM·Brand Lift 병행

### Geo Lift Test
- **언제:** Incrementality (진짜 증분) 검증
- **방법:** 지역 매칭 (test geo vs control geo) · 광고 ON/OFF
- **기간:** 최소 2-4주
- **한계:** 인구 <10만 지역 = 통계 불유의·도구: Meta Geo Lift·Google Geo Experiments

### Aided / Unaided Awareness
- **방법:** 패널 조사 (YouGov·Nielsen·DMC리포트·칸타·갤럽·엠브레인)
- **표본:** 500-1,000명 (오차 ±3-5%)
- **종류:**
  - Top of Mind: "[카테고리] 하면 떠오르는 첫 브랜드"
  - Unaided Recall: "알고 있는 브랜드 모두"
  - Aided Recognition: 브랜드 리스트 보여주고 인지 여부
- **벤치마크:** 카테고리·시장·기간별 상이 → Brand Track 정기 측정

### NPS (Net Promoter Score)
- **방법:** "이 브랜드를 친구·동료에게 추천할 가능성? 0-10"
- **계산:** %Promoters (9-10) - %Detractors (0-6)
- **벤치마크:** 산업별 (Bain & Company)
- **한계:** 단일 지표 의존 ✗ → 정성 follow-up 권장

### Mental Availability (Byron Sharp)
- **방법:** CEPs (Category Entry Points) 인지 — "[CEP 상황] 시 떠오르는 브랜드?"
- **CEPs 예시:** 시간(아침·점심)·장소(집·외출)·동기·상태(피곤·기념)
- **한국 미흡:** 표준 도구 부족 → 자체 패널 설계 필요

## 측정 설계 시점 (절대규칙 7)

| 시점 | 액션 |
|------|------|
| 캠페인 사전 (L1 단계) | Measurement Plan 확정 |
| 캠페인 1주 전 | Brand Track Baseline 측정 |
| 캠페인 중 | Activation 지표 실시간·일간 |
| 캠페인 종료 직후 | Brand Lift 1차 |
| 종료 +3개월 | Brand Track 2차·중기 효과 |
| 종료 +12개월 | Long-term (NPS·재구매·LTV) |
| 연간 | MMM 갱신·ESOV 평가 |

## 한국 측정 환경

- **공식:** KOBACO 광고통계시스템·방심위
- **업계:** DMC리포트·메조미디어·나스미디어·제일기획·이노션
- **글로벌:** Meta·Google·TikTok 자체 도구
- **3rd party:** 닐슨코리아·칸타코리아·YouGov·갤럽·엠브레인

## 캠페인 단계별 KPI 매트릭스

| 도메인·단계 | Brand 지표 | Activation 지표 | Long-term 지표 |
|-----------|----------|---------------|--------------|
| D1 런칭 | Aided Awareness Δ+15·VCR 70% | CTR 1.5%·검색 3배 | NPS baseline |
| D2 리포지셔닝 | Attribute Shift Δ+10·CEPs 확장 | 신 카테고리 전환 +30% | 가격 프리미엄 유지 |
| D3 리뉴얼 | DBA Recognition Δ+20 | 매장 방문 유지 | Heavy User 이탈 <5% |
| D4 세일즈푸시 | Aided Awareness 유지 | ROAS 3.0+·전환 +30% | 신규→재구매 10%+ |
| D5 체험·팝업 | Aided Awareness Δ+5-10 | 온라인 매출 Δ+20% | SNS Buzz·Fame |
| D6 CSR·ESG | Purpose Association Δ+10 | - | Trust·NPS·ESG Score |
| D7 위기대응 | Sentiment 회복·Aided 유지 | - | NPS 회복 70%+ |

## Gotchas

- 단일 도구 의존 → 왜곡 (예: Last-click만)
- 사후 측정 = 합리화. Plan은 L1 사전 확정
- 표본 부족 (<500) → 의사결정 불가
- MMM 데이터 부족 (<6개월) → 과적합
- Geo Lift 인구 너무 작음 → 통계 불유의
- NPS만으로 브랜드 평가 → 단순화 오류
- Mental Availability를 단순 Awareness로 오해 → CEPs 측정 누락
