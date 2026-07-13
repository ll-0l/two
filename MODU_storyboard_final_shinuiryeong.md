# 멀티모달 콘텐츠 제작

---

# MODU AI 브랜드 광고 제작 스토리보드 최종본

## 0. 제출 산출물 요약

본 문서는 과제 수행을 위해 기획한 **가상의 AI 일정·할 일 정리 플래너 앱 브랜드 MODU**의 10초 이내 브랜드 광고 제작 과정을 정리한 최종 스토리보드 문서이다.  
MODU는 실제 출시된 서비스가 아니라, AI 기반 생산성 앱 광고 제작 파이프라인을 설명하기 위해 설정한 **가상 브랜드**이다.

최종 광고는 **문제 제시 → MODU 등장 → 일정 정리 → 브랜드 각인**의 구조로 제작하였다.  
최종 제출 시에는 본 Markdown 문서를 PDF로 변환한 **스토리보드 PDF 1개**와, AI 생성 소스를 기반으로 편집한 **광고 영상 MP4 1개**를 함께 제출한다.

| 산출물 | 최종 파일명 | 상태 | 비고 |
|---|---|---|---|
| 스토리보드 PDF | `MODU_storyboard_shinuiryeong.pdf` | 변환 예정 | 본 MD 최종본을 PDF로 변환 |
| 스토리보드 MD | `MODU_storyboard_final_shinuiryeong.md` | 완료 | 최종 영상 검토 내용 및 수정 사항 반영 |
| 최종 광고 영상 MP4 | `MODU_brand_ad_shinuiryeong.mp4` | 완료 | 10초 이내 제출용 최종본 |
| 최종 편집 원본 | `MODU_capcut_project.mp4` | 검토 완료 | CapCut에서 출력한 최종 편집본 |
| BGM 파일 | Suno 생성 BGM | 완료 | 가사 없는 전자음악 BGM |
| 내레이션 파일 | 클로바더빙 생성 음성 | 완료 | 발랄한 여성 톤의 AI 음성 내레이션 |

### 0-1. 최종 영상 검토 결과

업로드된 최종 편집본 `MODU_capcut_project.mp4`를 확인한 결과, 영상은 **1280x720, 16:9, H.264, AAC, 30fps** 형식으로 출력되었다.  
과제 조건인 **720p 이상**, **MP4**, **AI 시각 요소 + AI 청각 요소 포함**은 충족한다.

다만 업로드 검토본은 전체 길이가 약 **10.05초**로 확인되어, 과제 조건인 **10초 이내**에 맞추기 위해 제출용 최종본에서는 마지막 약 0.05초를 잘라 **10.00초**로 정리하는 것이 안전하다.

| 항목 | 검토 결과 | 과제 조건 충족 여부 |
|---|---|---|
| 영상 길이 | 검토본 약 10.05초 / 제출용 10.00초 권장 | 10.00초 제출 시 충족 |
| 해상도 | 1280x720 | 충족 |
| 화면 비율 | 16:9 | 충족 |
| 비디오 코덱 | H.264 | 충족 |
| 오디오 코덱 | AAC | 충족 |
| 프레임레이트 | 30fps | 충족 |
| AI 이미지·영상 요소 | 로고, 앱 UI, 씬별 영상 생성 소스 사용 | 충족 |
| AI 청각 요소 | Suno BGM, 클로바더빙 내레이션 사용 | 충족 |
| 마지막 구간 브랜드 각인 | MODU 로고와 `나의 하루를 한눈에.` 노출 | 충족 |

---

## 1. 프로젝트 개요

본 프로젝트는 과제 수행을 위해 새롭게 기획한 가상의 AI 일정·할 일 정리 플래너 앱 **MODU**의 10초 이내 브랜드 광고를 제작하는 것을 목표로 한다.  
MODU는 할 일, 일정, 과제, 약속처럼 흩어져 있는 정보를 AI가 자동으로 정리해 사용자의 하루를 한눈에 보여준다는 콘셉트로 설계한 가상 생산성 앱 브랜드이다.

광고는 일정과 할 일이 동시에 쌓여 부담을 느끼는 **20~30대 취업준비생, 프리랜서, 직장인**을 주요 타깃으로 한다.  
짧은 러닝타임 안에서 “할 일 폭주”라는 문제 상황을 먼저 제시하고, MODU가 그 혼란을 정리해주는 해결 도구로 등장하는 구조를 사용한다.

이번 제작에서는 **Ideogram, ChatGPT 이미지 생성, Google Flow, Suno, 클로바더빙, CapCut**을 활용하였다.  
이미지, 영상, 오디오, 내레이션, 편집 도구의 역할을 분리하고, 각 도구가 가진 장점을 활용하여 다음과 같은 제작 흐름을 설계하였다.

> 기획 의도 정의 → 로고·앱 UI 기준 이미지 신규 생성 → 씬별 프롬프트 설계 → 이미지 생성 → Google Flow로 씬 1~4 영상 생성 → Suno BGM 생성 → 클로바더빙 내레이션 생성 → CapCut 통합 편집 → 최종 MP4 출력

이 프로젝트의 핵심은 단순히 여러 AI 도구를 사용하는 것이 아니라, **기획 의도와 브랜드 톤앤매너가 프롬프트를 거쳐 최종 영상으로 구현되는 제작 파이프라인을 설명할 수 있도록 문서화하는 것**이다.

---

## 2. 과제 요구사항 비교표

| 과제 요구사항 | 최종 결과 반영 여부 | 설명 |
|---|---|---|
| 가상 또는 실제 브랜드 광고 제작 | 충족 | 가상 브랜드 `MODU`를 설정하고 브랜드 광고로 제작 |
| 이미지 생성 AI 사용 | 충족 | 로고, 앱 UI, 씬별 키비주얼 생성에 Ideogram 및 ChatGPT 이미지 생성 활용 |
| 영상 생성 AI 사용 | 충족 | Google Flow로 씬 1~4의 광고용 모션 영상 생성 |
| 오디오 생성 AI 사용 | 충족 | Suno로 가사 없는 전자음악 BGM 생성 |
| 음성 합성 AI 사용 | 충족 | 클로바더빙으로 내레이션 생성 |
| 최종 편집 도구 사용 | 충족 | CapCut에서 컷 편집, 텍스트, 오디오 믹싱, 최종 출력 진행 |
| 10초 이내 영상 | 충족 예정 | 검토본은 약 10.05초이나, 제출용은 10.00초로 컷 필요 |
| 720p 이상 해상도 | 충족 | 최종 영상 1280x720 |
| 스토리보드 PDF 제출 | 진행 예정 | 본 MD를 PDF로 변환하여 제출 |
| 프롬프트 수정 전후 기록 | 충족 | 씬 1 방향 수정, 도구 변경, 내레이션 수정, 엔딩 카피 분리 과정을 기록 |

---

## 3. 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| 브랜드명 | MODU |
| 브랜드 구분 | 과제 수행을 위해 기획한 가상 브랜드 |
| 발음 | 모두 |
| 제출자명 | 신의령 |
| 브랜드 유형 | 가상의 AI 일정·할 일 정리 플래너 앱 |
| 주요 타깃 | 할 일과 일정이 많은 20~30대 취업준비생, 프리랜서, 직장인 |
| 타깃 상황 | 공부, 지원서, 미팅, 약속, 개인 일정이 동시에 쌓여 무엇부터 해야 할지 헷갈리는 상황 |
| 톤앤매너 | 네온, 사이버펑크, 경쾌한 디지털 생산성 광고 |
| 시각 키워드 | 다크 네이비, 딥 퍼플, 네온 블루, 네온 핑크, 글로우, 카드형 UI |
| 브랜드 성격 | 똑똑하지만 부담스럽지 않은 AI 비서, 할 일을 빠르게 정리해주는 친구 같은 앱 |
| USP | 흩어진 일정과 할 일을 AI가 자동으로 분류해 한눈에 보여준다. |
| 핵심 메시지 | 흩어진 할 일을 MODU가 모두 정리해준다. |
| 최종 화면 카피 1 | 할 일 폭주? |
| 최종 화면 카피 2 | 나의 하루를 한눈에. |
| 최종 내레이션 방향 | 발랄하고 경쾌한 20대 여성 목소리 |
| 광고 구조 | 할 일 폭주 → MODU 실행 → 일정 정리 → 브랜드 각인 |

---

## 4. 사용 도구 목록

이번 프로젝트에서는 이미지, 비디오, 오디오, 음성, 편집 도구를 각각 분리해 사용하였다.  
초기 계획에서는 CapCut TTS를 사용하려 했으나, 음성 생성 오류와 `MODU`를 “엠오디유”로 읽는 발음 문제가 발생하여 최종 내레이션 도구를 **클로바더빙**으로 변경하였다.

| 구분 | 실제 사용 도구 | 사용 목적 | 최종 선택 이유 | 대체 도구 |
|---|---|---|---|---|
| 이미지 생성 | Ideogram, ChatGPT 이미지 생성 | MODU 로고, 앱 UI 기준 이미지, 씬별 키비주얼, 엔딩 이미지 신규 생성 | 가상 브랜드이므로 기준 비주얼을 먼저 생성하고, 씬별 스타일 일관성을 유지하기 위해 사용 | Google Whisk, Canva AI 이미지 생성 |
| 비디오 생성/변환 | Google Flow | 이미지·프롬프트 기반 씬별 모션 영상 생성 | 네온 글로우, 입자 이동, 스마트폰 전환, 앱 UI 활성화 모션을 구현하기 위해 사용 | KLING, Pika, CapCut 모션 |
| 오디오 생성 | Suno | 10초 광고에 어울리는 경쾌한 디지털 BGM 생성 | 생산성 앱 광고에 맞는 밝고 에너지 있는 전자음악 분위기 제작 | CapCut 기본 오디오, Stable Audio, Beatoven |
| 음성 합성 | 클로바더빙 | 발랄하고 경쾌한 여성 톤의 내레이션 생성 | CapCut TTS 오류 및 MODU 발음 문제를 해결하기 위해 사용 | 타입캐스트, TTSMaker, CapCut TTS |
| 최종 편집 | CapCut | 컷 편집, 자막, 전환, 오디오 레벨 조정, 최종 MP4 출력 | AI 생성 결과물을 하나의 10초 광고 영상으로 통합하기 위해 사용 | Canva Video, Premiere Pro |

### 4-1. 클로바더빙 사용 표기

클로바더빙 무료 사용 시 출처 표기가 필요하므로, 최종 제출 문서에는 아래 문구를 함께 기재한다.

```text
본 영상의 AI 음성 내레이션은 네이버 클로바더빙을 활용하여 제작하였습니다.
```

최종 영상에는 클로바더빙 출처 표기 또는 워터마크가 포함되어 있으며, 이는 AI 음성 생성 도구 사용 사실을 명확히 보여주는 근거로 활용할 수 있다.

---

## 5. 최종 영상 제작 스펙

| 항목 | 최종 기준 |
|---|---|
| 최종 영상 파일명 | `MODU_brand_ad_shinuiryeong.mp4` |
| 최종 영상 길이 | 10.00초 권장 |
| 검토본 길이 | 약 10.05초 |
| 화면 비율 | 16:9 |
| 해상도 | 1280x720 |
| 프레임레이트 | 30fps |
| 비디오 코덱 | H.264 |
| 오디오 코덱 | AAC |
| 필수 포함 요소 | AI로 생성한 시각 요소 + AI로 생성한 청각 요소 |
| 마지막 구간 조건 | 마지막 3초 구간에 MODU 로고와 `나의 하루를 한눈에.` 포함 |

### 5-1. 길이 수정 판단

업로드한 최종 편집본은 약 10.05초로 확인되었다.  
과제 조건이 “10초 이내”이므로, 최종 제출 전에는 CapCut 또는 영상 편집 도구에서 마지막 약 0.05초를 잘라 **10.00초 이하**로 맞추는 것이 안전하다.

---

## 6. 최종 카피 및 내레이션 구성

최종 편집 과정에서 엔딩 장면에 슬로건과 엔딩 카피가 동시에 몰리지 않도록 카피 배치를 조정하였다.  
초기에는 씬 4에 `할 일 폭주? MODU 정리해.`와 `나의 하루를 한눈에.`를 함께 넣는 방식을 고려했으나, 마지막 장면에 정보가 과도하게 몰릴 수 있어 최종적으로 아래와 같이 분리하였다.

| 구분 | 최종 처리 |
|---|---|
| 씬 1 화면 텍스트 | `할 일 폭주?` |
| 씬 2 화면 텍스트 | 없음 |
| 씬 3 화면 텍스트 | 없음 |
| 씬 4 화면 텍스트 | `나의 하루를 한눈에.` |
| 씬 1 내레이션 | 할 일이 너무 많아? |
| 씬 2 내레이션 | 모두가 깔끔하게 정리해줄게. |
| 씬 3 내레이션 | 일정, 과제, 약속까지 한눈에. |
| 씬 4 내레이션 | 모두. |

### 6-1. 최종 내레이션 대본

```text
할 일이 너무 많아?
모두가 깔끔하게 정리해줄게.
일정, 과제, 약속까지 한눈에.
모두.
```

### 6-2. 내레이션 수정 이유

초기 대본에는 `MODU가 모두 정리해.`라는 문장이 포함되어 있었다.  
그러나 TTS 도구에서 `MODU`가 “엠오디유”로 읽히는 문제가 발생해 브랜드 발음이 어색해졌다.  
따라서 나레이션용 대본에서는 브랜드 발음을 한글 `모두`로 처리하고, 화면에서는 영문 로고 `MODU`를 유지하는 방식으로 수정하였다.

또한 마지막 장면에는 이미 `나의 하루를 한눈에.`라는 텍스트가 화면에 노출되므로, 같은 문장을 음성으로 반복하지 않고 짧게 `모두.`로 마무리하여 브랜드명을 각인하도록 구성하였다.

---

## 7. 최종 씬 구성 요약

| 씬 번호 | 최종 길이 | 역할 | 화면 구성 | 화면 텍스트 | 내레이션 |
|---|---:|---|---|---|---|
| 씬 1 | 2초 | 문제 제시 | 네온 조명의 복잡한 책상, 인물, 종이, 포스트잇, 홀로그램 카드가 폭주하는 장면 | 할 일 폭주? | 할 일이 너무 많아? |
| 씬 2 | 2초 | 전환 | 흩어진 종이·메모·홀로그램 카드가 MODU 로고가 있는 스마트폰으로 빨려 들어감 | 없음 | 모두가 깔끔하게 정리해줄게. |
| 씬 3 | 3초 | 해결 | MODU 앱 UI가 나타나고 캘린더·일정 카드가 정리된 상태로 활성화됨 | 없음 | 일정, 과제, 약속까지 한눈에. |
| 씬 4 | 3초 | 브랜드 각인 | MODU 로고 엔딩 카드와 네온 입자 배경 | 나의 하루를 한눈에. | 모두. |

총 길이: **10초**

---

## 8. 최종 영상 타임라인

| 전체 시간 | 화면 | 화면 텍스트 | 오디오/내레이션 | 편집 포인트 |
|---|---|---|---|---|
| 0:00~0:02 | 할 일과 알림이 폭주하는 네온 작업 공간 | 할 일 폭주? | 할 일이 너무 많아? | 빠른 움직임, 혼란감, 네온 조명 |
| 0:02~0:04 | 흩어진 종이와 디지털 카드가 MODU 앱으로 흡수됨 | 없음 | 모두가 깔끔하게 정리해줄게. | 흡수 모션, 입자 변환, 스마트폰 중심 전환 |
| 0:04~0:07 | MODU 앱 UI가 완성되고 일정 카드가 정리됨 | 없음 | 일정, 과제, 약속까지 한눈에. | UI 안정화, 카드 글로우, 플러스 버튼 강조 |
| 0:07~0:10 | MODU 로고 엔딩 카드 | 나의 하루를 한눈에. | 모두. | 로고 고정, 엔딩 카피 유지, BGM 마무리 |

---

## 9. 씬별 스토리보드 및 최종 프롬프트

## 씬 1. 할 일 폭주 / 현실의 혼란

| 항목 | 내용 |
|---|---|
| 씬 번호 | 1 |
| 씬 길이 | 2초 |
| 목표 메시지 | 사용자가 할 일과 일정에 압도되는 문제 상황을 보여준다. |
| 화면 구성 | 네온 블루·핑크 조명의 복잡한 작업 공간에서 인물이 스트레스를 받고 있으며, 종이·포스트잇·홀로그램 카드가 주변을 빠르게 떠다닌다. |
| 화면 텍스트 | `할 일 폭주?` |
| 내레이션 | `할 일이 너무 많아?` |
| 편집 판단 | 화면 텍스트는 인물의 얼굴과 손을 가리지 않는 중앙 하단 영역에 배치한다. |

### 씬 1 이미지 생성 프롬프트

```text
chaotic everyday life scene for a 10-second commercial opening, showing a young adult overwhelmed by too many things to do, messy but visually appealing desk or compact room, laptop, planner, sticky notes, calendar page, coffee cup, study materials, resume papers, notebook, ringing smartphone, bag, clock, delivery box, to-do memo, multiple daily responsibilities all appearing at once, busy morning atmosphere, stressful and overwhelming mood, realistic daily life chaos, cinematic advertising composition, futuristic city-inspired mood, dark navy and deep purple environment, neon blue and neon pink lighting accents, subtle cyberpunk atmosphere, soft neon reflections, digital glow, premium tech brand aesthetic, high contrast, stylish and emotional commercial look, 16:9 composition, no app UI, no smartphone dashboard, no central interface, no clear human face, no brand logos, no readable long text.
```

### 씬 1 영상 변환 프롬프트

```text
2-second commercial opening shot using the original image composition. Preserve the overwhelmed person, laptop, desk, room layout, lighting, and existing objects. Papers, sticky notes, calendar pages, checklist icons, and translucent holographic task cards lift from the cluttered room and swirl chaotically around the person. Use subtle cinematic push-in, slight handheld shake, neon blue and neon pink reflections, realistic paper flutter, and motion blur. Do not reveal an app UI or smartphone dashboard.
```

---

## 씬 2. MODU 실행 / 현실의 혼란을 앱으로 흡수

| 항목 | 내용 |
|---|---|
| 씬 번호 | 2 |
| 씬 길이 | 2초 |
| 목표 메시지 | MODU가 복잡한 할 일과 일정 조각을 한곳으로 모으는 해결 도구임을 보여준다. |
| 화면 구성 | 스마트폰이 화면 중앙에 정면으로 나타나고, 종이·포스트잇·홀로그램 카드가 화면 안으로 빨려 들어간다. 스마트폰 화면에는 최종 대시보드가 아니라 MODU 로고와 네온 흡수 지점만 보인다. |
| 화면 텍스트 | 없음 |
| 내레이션 | `모두가 깔끔하게 정리해줄게.` |
| 편집 판단 | 화면은 흡수 모션에 집중하고, 설명은 내레이션으로 처리한다. |

### 씬 2 이미지 생성 프롬프트

```text
Use the official MODU logo image as the fixed brand identity reference. Create a complete smartphone upright in the center of the frame, full front view, entire phone visible, straight-on angle. Surround the phone with floating elements from Scene 1: large blue and pink paper sheets, yellow sticky notes, translucent cyan holographic cards, checklist symbols, calendar fragments, document pieces, and glowing notification particles. Keep the phone screen mostly dark and minimal. Show the official MODU logo at the top and a circular digital intake point glowing in neon blue and neon pink in the center. Do not reveal the final dashboard UI.
```

### 씬 2 영상 변환 프롬프트

```text
2-second commercial transition shot. Keep the smartphone centered and upright. Floating papers, sticky notes, checklist fragments, calendar pieces, holographic task cards, and notification particles bend into curved streams toward the center of the smartphone screen. As each element approaches the screen, it transforms into tiny neon cyan and pink particles and is absorbed into the glowing intake point. Do not reveal calendar UI, schedule cards, bottom navigation, or completed dashboard.
```

---

## 씬 3. 일정 자동 정리 / MODU 최종 UI 공개

| 항목 | 내용 |
|---|---|
| 씬 번호 | 3 |
| 씬 길이 | 3초 |
| 목표 메시지 | MODU가 일정과 할 일을 카드형 대시보드에 자동으로 정리한다는 기능적 가치를 보여준다. |
| 화면 구성 | 스마트폰 정면 화면에 MODU 앱 UI가 표시된다. `2026 7월`, `오늘`, 주간 캘린더, 일정 카드가 보이며 네온 입자가 카드와 체크 요소를 활성화한다. |
| 화면 텍스트 | 없음 |
| 내레이션 | `일정, 과제, 약속까지 한눈에.` |
| 편집 판단 | 앱 UI가 주인공이므로 별도 화면 자막을 넣지 않는다. |

### 씬 3 앱 UI 고정 프롬프트

```text
Use the MODU app UI reference image as the fixed final interface template. Preserve the complete smartphone presentation and app layout as closely as possible. Keep the same top MODU header, “2026 7월” label, large “오늘” title, weekly calendar row with “월 화 수 목 금 토 일” and dates 4 to 10, neon cyan highlight on Saturday 9, four stacked schedule cards, highlighted meeting card, and bottom navigation bar with glowing plus button. Do not redesign, rearrange, simplify, replace, or invent a different app interface.
```

### 씬 3 영상 변환 프롬프트

```text
3-second final MODU UI activation and reveal shot. Keep the complete smartphone centered, fully visible, upright, and straight-on. Preserve the official MODU logo, all Korean UI text, weekly calendar, dates, schedule card positions, icons, profile avatars, and bottom navigation exactly as shown. Use neon cyan and pink particles only to activate and illuminate the existing UI. The light travels across the calendar, reinforces Saturday 9, illuminates the schedule cards, highlights the meeting card, and gently pulses the bottom plus button once.
```

---

## 씬 4. 브랜드 각인 / 엔딩 카드

| 항목 | 내용 |
|---|---|
| 씬 번호 | 4 |
| 씬 길이 | 3초 |
| 목표 메시지 | 정리된 하루의 결과를 MODU 로고와 엔딩 카피로 연결해 브랜드를 각인한다. |
| 화면 구성 | 다크 네이비·딥 퍼플 회로 보드 배경 위에 MODU 로고가 크게 보이고, 하단에는 `나의 하루를 한눈에.` 텍스트가 표시된다. |
| 화면 텍스트 | `나의 하루를 한눈에.` |
| 내레이션 | `모두.` |
| 편집 판단 | `나의 하루를 한눈에.`는 이미 화면 텍스트로 보이므로 음성에서는 반복하지 않고 브랜드명만 짧게 남긴다. |

### 씬 4 이미지 생성 프롬프트

```text
Use the official MODU logo image as the highest-priority fixed brand identity reference. Preserve the wordmark closely. Create a final premium brand end card for the MODU AI productivity planner app. Place the official MODU wordmark prominently in the center of the frame where the smartphone stood in Scene 3. Preserve the dark navy and deep purple digital circuit-board background, purple glow on the left, blue glow on the right, and reflective grid floor. Leave a clean area below the logo for the Korean ending copy to be added later in CapCut. Do not generate Korean text inside the image.
```

### 씬 4 영상 변환 프롬프트

```text
3-second premium MODU brand end-card animation. Keep the official MODU logo centered, sharp, readable, and structurally unchanged throughout the shot. A faint residual phone-shaped neon aura and cyan-pink particles fade behind the logo. Add one subtle neon blue and pink glow pulse around the fixed MODU wordmark. Leave the area below the logo clean for the Korean ending copy added in CapCut.
```

---

## 10. 프롬프트 및 기획 수정 전후 기록

## 10-1. 씬 1 방향 수정

### 수정 전

초기 씬 1은 디지털 할 일 카드와 알림창이 화면에 떠다니는 추상적인 장면으로 기획하였다.

```text
chaotic digital task overload scene for a futuristic AI productivity planner app advertisement, many floating schedule cards, calendar reminders, notification popups, checklist icons, dark navy and deep purple background, neon blue and neon pink highlights
```

### 문제점

- 씬 1부터 앱 UI와 유사한 디지털 카드가 등장해 씬 3의 해결 장면과 역할이 겹쳤다.
- 사용자가 실제로 “할 일이 많아 정신없는 상황”에 공감하기 어려웠다.

### 수정 후

현실적인 책상, 노트북, 서류, 포스트잇, 알림, 인물의 압박감을 중심으로 바꾸고, 네온 블루·핑크 조명으로 브랜드 톤을 유지하였다.

```text
chaotic everyday life scene, overwhelmed young adult, messy desk, laptop, planner, sticky notes, calendar page, coffee cup, resume papers, ringing smartphone, dark navy and deep purple environment, neon blue and neon pink lighting accents, subtle cyberpunk atmosphere
```

### 결과

씬 1은 “복잡한 일상”, 씬 2는 “MODU로 전환”, 씬 3은 “정리된 UI”, 씬 4는 “브랜드 각인”이라는 구조가 더 명확해졌다.

---

## 10-2. 씬 4 카피 배치 수정

### 수정 전

씬 4에 아래 문구를 모두 넣는 방식을 고려하였다.

```text
할 일 폭주? MODU 정리해.
나의 하루를 한눈에.
```

### 문제점

- 마지막 장면에 정보가 몰려 엔딩 카드가 복잡해질 수 있었다.
- `할 일 폭주?`는 문제 제시 문구이므로 엔딩보다 씬 1에 더 적합했다.
- `나의 하루를 한눈에.`는 엔딩 카피로 단독 사용했을 때 더 깔끔했다.

### 수정 후

```text
씬 1 화면 텍스트: 할 일 폭주?
씬 4 화면 텍스트: 나의 하루를 한눈에.
```

### 결과

광고 메시지가 **문제 제시 → 해결 과정 → 브랜드 각인** 순서로 분산되어, 전체 흐름이 더 자연스러워졌다.

---

## 10-3. 내레이션 도구 및 대본 수정

### 수정 전

```text
할 일이 너무 많아?
MODU가 모두 정리해.
일정, 과제, 약속까지 한눈에.
나의 하루를 한눈에.
```

초기에는 CapCut TTS를 사용하려 했으나, 음성 생성이 원활하지 않았고 `MODU`가 “엠오디유”로 읽히는 문제가 있었다.

### 수정 후

```text
할 일이 너무 많아?
모두가 모오오두 정리해줄게!
일정, 과제, 약속까지 한눈에.
모두.
```

### 수정 이유

- `MODU`는 화면 로고에서는 영문으로 유지하고, 음성에서는 브랜드 발음인 `모두`로 처리하였다.
- 마지막 `나의 하루를 한눈에.`는 화면 텍스트로 이미 노출되므로, 음성에서는 `모두.`로 짧게 끝내 브랜드명을 각인한다.
- CapCut TTS 대신 클로바더빙을 사용해 더 안정적인 한국어 내레이션을 확보하였다.

---

## 11. 오디오 기획 및 믹싱

| 항목 | 내용 |
|---|---|
| BGM 생성 도구 | Suno |
| 음성 합성 도구 | 클로바더빙 |
| BGM 방향 | 가사 없는 경쾌한 디지털 팝 또는 일렉트로닉 비트 |
| 분위기 | 통통 튀고 생산적인 느낌, 복잡함이 정리되는 시원한 분위기 |
| 내레이션 톤 | 발랄하고 경쾌한 20대 여성 목소리 |
| 효과음 | 필요 시 알림음, 디지털 흡수음, 체크 완료음, 브랜드 차임을 짧게 사용 |

### 11-1. Suno BGM 생성 프롬프트

```text
10-second upbeat futuristic electronic pop instrumental for an AI productivity app advertisement, bright digital synth, clean tech mood, playful and energetic, neon cyberpunk feeling, suitable for a young female voice-over, short commercial jingle, no lyrics, no vocals.
```

### 11-2. 최종 내레이션 스크립트

```text
할 일이 너무 많아?
모두가 모오오두 정리해줄게!
일정, 과제, 약속까지 한눈에.
모두.
```

### 11-3. 오디오 믹싱 방침

| 오디오 요소 | 권장 음량 |
|---|---:|
| 내레이션 | 0dB 기준 |
| Suno BGM | -18dB ~ -24dB |

- 내레이션이 가장 잘 들리도록 BGM은 낮게 깐다.
---

## 12. 최종 편집 계획 및 실제 반영 내용

최종 통합 편집은 **CapCut**에서 진행하였다.  
CapCut은 AI 생성 결과물을 새로 만드는 용도가 아니라, Google Flow 영상, Suno BGM, 클로바더빙 내레이션, 화면 텍스트를 하나의 10초 광고로 통합하는 편집 도구로 사용하였다.

### 12-1. 실제 편집 순서

1. 씬 1~4 Google Flow 영상을 16:9 타임라인에 배치한다.
2. 씬 길이를 2초, 2초, 3초, 3초 구조로 맞춘다.
3. 씬 1에 `할 일 폭주?` 텍스트를 직접 배치한다.
4. 씬 2와 씬 3에는 화면 텍스트를 추가하지 않고 영상 모션과 내레이션에 집중한다.
5. 씬 4에는 `나의 하루를 한눈에.` 텍스트만 직접 입력한다.
6. 클로바더빙에서 생성한 내레이션을 삽입한다.
7. Suno에서 생성한 BGM을 삽입하고 내레이션을 방해하지 않도록 볼륨을 낮춘다.
8. 최종 영상을 MP4 형식으로 출력한다.
9. 제출 전 길이를 10.00초 이하로 맞춘다.

### 12-2. 실제 영상 검토 반영

| 검토 항목 | 결과 | 문서 수정 내용 |
|---|---|---|
| 씬 1 텍스트 | `할 일 폭주?` 화면 노출 확인 | 씬 1 화면 카피로 반영 |
| 씬 2 텍스트 | 별도 화면 카피 없이 MODU 실행 장면 중심 | 씬 2는 내레이션 중심으로 수정 |
| 씬 3 텍스트 | 앱 UI 중심, 별도 카피 없음 | 씬 3은 UI와 내레이션 중심으로 수정 |
| 씬 4 텍스트 | `나의 하루를 한눈에.` 화면 노출 확인 | 씬 4 엔딩 카피로 반영 |
| 내레이션 도구 | 클로바더빙 사용 | CapCut TTS → 클로바더빙으로 수정 |
| BGM 도구 | Suno 사용 | 오디오 생성 도구에 Suno 유지 |
| 영상 길이 | 검토본 약 10.05초 | 제출용 10.00초 컷 필요로 반영 |
| 해상도 | 1280x720 | 최종 스펙에 반영 |
| 프레임레이트 | 30fps | 최종 스펙에 반영 |
| 오디오 코덱 | AAC | 최종 스펙에 반영 |

---

## 13. 최종 결과 파일명 규칙

| 파일 종류 | 파일명 |
|---|---|
| 스토리보드 MD 문서 | `MODU_storyboard_final_shinuiryeong.md` |
| 스토리보드 PDF 문서 | `MODU_storyboard_shinuiryeong.pdf` |
| 최종 광고 영상 | `MODU_brand_ad_shinuiryeong.mp4` |
| 최종 편집 검토본 | `MODU_capcut_project.mp4` |
| MODU 로고 기준 이미지 | `modu_logo_wordmark.png` |
| MODU 앱 UI 기준 이미지 | `modu_app_ui_reference.png` |
| 씬 1 영상 | `scene01_task_overload_motion.mp4` |
| 씬 2 영상 | `scene02_modu_launch_motion.mp4` |
| 씬 3 영상 | `scene03_organized_dashboard_motion.mp4` |
| 씬 4 영상 | `scene04_modu_endcard_motion.mp4` |
| BGM 파일 | `modu_bgm_suno_electronic_pop.mp3` 또는 `modu_bgm_suno_electronic_pop.wav` |
| 내레이션 파일 | `modu_voiceover_clovadubbing.mp3` 또는 `modu_voiceover_clovadubbing.wav` |

---

## 14. 제작 의사결정 요약

MODU 광고는 10초 이내의 짧은 시간 안에 앱의 핵심 가치를 전달해야 하므로, 복잡한 설명보다 **할 일 폭주에서 정리로 바뀌는 화면 변화**를 중심으로 기획하였다.

처음에는 엔딩 장면에 `할 일 폭주? MODU 정리해.`와 `나의 하루를 한눈에.`를 함께 넣는 구성을 고려했지만, 최종 편집 과정에서 메시지가 엔딩에 몰리는 문제가 있다고 판단하였다. 따라서 화면 카피를 씬별 역할에 맞게 재배치하였다.

- 씬 1: 문제 제시 문구 `할 일 폭주?`
- 씬 2: MODU로 정보가 흡수되는 전환 장면
- 씬 3: 정리된 앱 UI 확인
- 씬 4: 엔딩 카피 `나의 하루를 한눈에.`

또한 `MODU`를 TTS가 “엠오디유”로 읽는 문제를 해결하기 위해, 내레이션에서는 브랜드 발음을 한글 `모두`로 처리하였다. 이로써 화면에서는 영문 로고 `MODU`가 보이고, 음성에서는 자연스럽게 “모두”라고 들리는 구조를 만들었다.

최종적으로 광고는 다음 메시지 흐름으로 완성되었다.

> 할 일이 너무 많아? → 모두가 깔끔하게 정리해줄게. → 일정, 과제, 약속까지 한눈에. → 모두.

---

## 15. 최종 제출 전 체크리스트

| 체크 항목 | 상태 |
|---|---|
| 가상 브랜드 명시 | 완료 |
| 이미지 생성 AI 사용 내역 작성 | 완료 |
| 영상 생성 AI 사용 내역 작성 | 완료 |
| Suno BGM 사용 내역 작성 | 완료 |
| 클로바더빙 내레이션 사용 내역 작성 | 완료 |
| CapCut 최종 편집 내역 작성 | 완료 |
| 씬별 화면 카피 최종 수정 | 완료 |
| 내레이션 최종 대본 수정 | 완료 |
| 최종 영상 해상도 720p 이상 | 완료 |
| 최종 영상 오디오 포함 | 완료 |
| 최종 영상 10초 이내 | 제출 전 10.00초로 컷 필요 |
| 스토리보드 PDF 변환 | 진행 예정 |

---

## 16. 클로바더빙 출처 표기

최종 제출 문서 또는 영상 설명란에는 아래 문구를 포함한다.

```text
본 영상의 AI 음성 내레이션은 네이버 클로바더빙을 활용하여 제작하였습니다.
```

---

## 17. 최종 제출 파일

최종 제출 파일은 아래 두 개로 정리한다.

```text
MODU_storyboard_shinuiryeong.pdf
MODU_brand_ad_shinuiryeong.mp4
```

Markdown 원본은 작업 증빙용으로 함께 보관한다.

```text
MODU_storyboard_final_shinuiryeong.md
```
