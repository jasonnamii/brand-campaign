# L5 — MEASUREMENT (측정·리프트·귀인)

**트랙:** 양트랙 분리 (Brand vs Activation vs Long-term)

단일 지표 통합 금지. 3축 분리 측정 (절대규칙 7).

## 필수 산출

| 항목 | 내용 |
|------|------|
| Measurement Plan | 캠페인 전 설계 (사후 측정 금지) |
| KPI Dashboard | Brand / Activation / Long-term 3섹션 |
| Brand Track | 캠페인 전·중·후 Aided Awareness·NPS·구매의도 패널 조사 |
| Incrementality | Geo Lift·Conversion Lift 실험군·통제군 |
| MMM | 6개월+ 데이터 축적 후 연 1회 갱신 |
| ESOV 달성률 | 목표 대비 실제 SOV·SOM 변화 |
| 복기 리포트 (M3) | Effie 4필러 + 학습·다음액션 |

## 측정 3축 (Binet&Field Effectiveness Triangle)

| 축 | 기간 | 핵심 지표 | 도구 |
|---|:-:|----------|------|
| **Brand Building** | 6-18개월 lag | Brand Lift 5-15%·Aided Awareness·Mental Availability·CEPs·NPS | Google/Meta Brand Lift·YouGov·Kantar·칸타코리아 |
| **Sales Activation** | 1-6개월 | ROAS 2.0+·CTR·CPA·전환율·검색량 증가 | GA4·Naver Analytics·Meta Ads·TikTok Ads |
| **Long-term Effects** | 18-36개월 | NPS·재구매율·LTV·브랜드 가격 프리미엄 | Bain NPS·Interbrand·Kantar BrandZ |

## 측정 도구별 (강점·한계)

| 도구 | 강점 | 한계 | 한국 가용 |
|------|------|------|:-:|
| Brand Lift Study | 인과 증명·Google/Meta/TikTok 제공 | 매체 내 갇힘·단일 캠페인 | ✓ |
| MMM | 멀티채널·장기기여도·offline 포함 | 6개월+ 데이터·모델링 비용 | ✓ Robyn(Meta) |
| MTA | 여정 추적·실시간 | iOS14.5 ATT 이후 제한·온라인만 | ⚠ 부분 |
| Geo Lift Test | 실제 시장·incrementality | 지역 분할·최소 2-4주 | ✓ |
| Aided Awareness | 상기도 표준 | 패널 비용·500-1,000명 | ✓ DMC·닐슨·칸타 |
| NPS | 브랜드 건강·재구매 신호 | 산업별 벤치마크 상이 | ✓ |
| Mental Availability | Byron Sharp CEPs 측정 | 방법론 표준 미정착 | ⚠ 한국 미흡 |

## 캠페인 단계별 KPI 매트릭스

| 단계 | Brand | Activation | Long-term |
|------|-------|-----------|----------|
| 런칭 (D1) | Aided Awareness Δ+15pt·VCR 70%+ | CTR 1.5%+·검색량 3배 | NPS baseline |
| 성장 (D2·D3) | Brand Lift 5-15%·CEPs 확장 | ROAS 2.0+·전환율 Δ+ | 재구매율 Δ+ |
| 유지 (일상) | Mental Availability·Share of Search | CPA 유지·CTR | NPS·LTV |
| 위기 (D7) | Sentiment 회복·Aided Awareness 유지 | - | 불매율 감소 |

## ESOV·SOV·SOM

- **SOV (Share of Voice):** 캠페인 노출량 / 카테고리 전체
- **SOM (Share of Market):** 시장 점유율
- **ESOV = SOV - SOM**
- +10pt ESOV → 점유율 +0.5%/yr (IPA 데이터)
- 마이너스 ESOV = 점유율 하락 예측 (Redflag 5)

## 복기 (M3) — Effie 4필러

1. **Challenge** — 비즈니스·마케팅·커뮤니케이션 목표
2. **Insight** — 소비자·카테고리·문화 통찰
3. **Execution** — 전략·크리에이티브·미디어 실행
4. **Results** — Brand·Sales·Long-term 3축 결과 + ESOV

## Gotchas
- Last-click Attribution 단일 의존 = Redflag 6
- Brand Building 단기 ROAS로 평가 → 6-18개월 lag 무시 (절대규칙 7 위반)
- MMM 데이터 부족(6개월 미만)에서 모델 신뢰 → 과적합
- Geo Lift 지역 너무 작음(인구 <10만) → 통계 유의 실패
- Aided Awareness 표본 <500 → 오차 ±5%+ (의사결정 불가)
- Mental Availability를 단순 Awareness로 오해 → CEPs 미측정
- 캠페인 후 측정 설계 = 사후 합리화. Plan은 L1 단계에서 확정
