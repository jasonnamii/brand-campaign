# Redflag 카탈로그 (10종)

캠페인 진단·설계 시 1차 스크린. Red = 즉시 수정·Red 미해소 시 캠페인 보류 권고.

| # | Redflag | 카테고리 | 판정 | 검출 신호 |
|---|---------|---------|:-:|---------|
| 1 | 뒷광고·광고표시 누락 (한국 공정위) | 컴플라이언스 | **Red** | 협찬·제공·금품·할인 받았는데 "광고" 미표시 |
| 2 | Brand Building 60% 미달 (단기 ROI 매몰) | 전략 | **Red** | 연간 예산의 Activation >60% (연간 단위) |
| 3 | 단일 채널 All-in (Channel-Fit 무시) | 미디어 | Yellow | 1개 채널 70%+, 같은 크리에이티브 멀티채널 |
| 4 | DBA 부재·교체 (Byron Sharp 위반) | 크리에이티브 | **Red** | High Fame DBA 교체 시도, DBA 자체 부재 |
| 5 | ESOV 마이너스 (경쟁사 SOV 미달) | 미디어 | Yellow | SOV - SOM < 0 |
| 6 | 측정 Last-click 단일 의존 | 측정 | Yellow | MMM·Brand Lift·Incrementality 0개 |
| 7 | Mega 인플루언서 only (Micro/Nano ROI 무시) | 미디어 | Yellow | Mega 80%+, Micro/Nano 0 |
| 8 | K-IP 과의존 (IP 라이프사이클 종속) | 한국 | Yellow | K-IP 의존 콜라보가 캠페인 핵심·IP 종료 후 공백 |
| 9 | 브랜드 세이프티 부재 (GARM·FTC) | 컴플라이언스 | **Red** | 인접 콘텐츠 검증·차단 리스트 부재 |
| 10 | 사후 Brand Track 부재 (실패학습 불가) | 측정 | **Red** | 캠페인 후 Aided Awareness·NPS·Brand Lift 측정 0 |

---

## 1. 뒷광고·광고표시 누락 (Red)

**근거:** 표시광고법(공정위) — 경제적 이해관계 시 "광고" 명시. 위반 과태료 최대 5억원.

**검출:**
- 인플루언서 콘텐츠에 "광고"·"유료광고" 표시 부재
- 영상 처음·중간·끝 3회 표시 부재
- "협찬"·"제공" 등 모호한 표현

**대응:** 즉시 수정·삭제 후 재업로드. 인플루언서 계약서에 표시 의무 명시 (→contract-reviewer).

## 2. Brand Building 60% 미달 (Red)

**근거:** Binet&Field IPA Databank 996 cases — 60:40 황금비율. ESOV +10pt = 점유율 +0.5%/yr.

**검출:** 연간 예산 Activation > 60%. 단기 ROAS만 평가 지표.

**대응:** 60:40 재배분 (B2C이커머스 70:30·B2B 50:50 조정 가능). L1 STRATEGY에서 ESOV 목표 재설정.

## 3. 단일 채널 All-in (Yellow)

**검출:** 1개 채널 70%+ 의존. 동일 크리에이티브 단순 리사이즈만 멀티채널 배포.

**대응:** Channel-Creative Fit 매트릭스 적용 → channel_fit_matrix.md.

## 4. DBA 부재·교체 (Red)

**근거:** Byron Sharp How Brands Grow — Mental·Physical Availability는 DBA에 의존.

**검출:**
- 색상·로고·사운드·캐릭터 DBA 자체 없음
- 리뉴얼·리포지셔닝에서 High Fame DBA 교체 시도

**대응:** DBA Audit (Fame × Uniqueness 매트릭스) → L2 CREATIVE 참조.

## 5. ESOV 마이너스 (Yellow)

**검출:** SOV < SOM. 경쟁사 노출량이 본사보다 큼.

**대응:** 미디어 예산 증액 또는 효율 개선 (Reach 우선·Frequency 적정화).

## 6. 측정 Last-click 단일 의존 (Yellow)

**근거:** iOS14.5 ATT·쿠키 deprecation 이후 한계.

**대응:** MMM + Brand Lift + Incrementality 3축 병행 → measurement_toolkit.md.

## 7. Mega 인플루언서 only (Yellow)

**근거:** Collabstr·SocialCat 2025 — Micro 전환 3-5%·Nano 7%, Mega 1% 미만.

**대응:** Mega 30% + Macro 20% + Micro 30% + Nano 20% 4티어 균형.

## 8. K-IP 과의존 (Yellow)

**검출:** 캠페인 핵심 메시지가 IP 종속·IP 라이프사이클 종료 후 공백.

**대응:** IP 콜라보를 캠페인 1요소로 한정·자체 DBA 강화 병행.

## 9. 브랜드 세이프티 부재 (Red)

**근거:** GARM (Global Alliance for Responsible Media)·FTC.

**검출:** 인접 콘텐츠 차단 리스트 없음·아동·폭력·혐오 인근 노출.

**대응:** Brand Suitability Filter 적용·플랫폼별 Exclusion List·정기 모니터링.

## 10. 사후 Brand Track 부재 (Red)

**검출:** 캠페인 후 Aided Awareness·Brand Lift·NPS 측정 0회.

**대응:** L5 Measurement Plan을 캠페인 사전(L1) 확정. 사후 측정 ✗.
