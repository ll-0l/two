# 멀티모달 콘텐츠 제작

---

# MODU AI 브랜드 광고 제작 스토리보드

## 0. 제출 산출물 요약

본 문서는 과제 수행을 위해 기획한 **가상의 AI 일정·할 일 정리 플래너 앱 브랜드 MODU**의 10초 이내 브랜드 광고 제작을 위한 스토리보드 문서이다.  
MODU는 실제 출시된 서비스가 아니라, AI 기반 생산성 앱 광고 제작 파이프라인을 설명하기 위해 설정한 가상 브랜드이다.  
최종 제출 시에는 본 Markdown 문서를 PDF로 변환한 **스토리보드 PDF 1개**와, AI 생성 소스를 기반으로 편집한 **광고 영상 MP4 1개**를 함께 제출한다.

| 산출물 | 파일명 | 제출 상태 | 비고 |
|---|---|---|---|
| 스토리보드 PDF | `MODU_storyboard_shinuiryeong.pdf` | 제작 예정 | 본 MD 문서를 PDF로 변환 |
| 광고 영상 MP4 | `MODU_brand_ad_shinuiryeong.mp4` | 제작 예정 | 10초 이내, 16:9 기준 |
| 작업 원본 MD | `MODU_storyboard_shinuiryeong.md` | 작성 중 | PDF 변환 전 원본 문서 |
| AI 생성 소스 폴더 | `MODU_assets/` | 제작 예정 | 이미지, 영상, 오디오, 내레이션 파일 정리 |

---

## 1. 프로젝트 개요

본 프로젝트는 과제 수행을 위해 새롭게 기획한 가상의 AI 일정·할 일 정리 플래너 앱 **MODU**의 10초 이내 브랜드 광고를 제작하는 것을 목표로 한다.  
MODU는 실제 운영 중인 서비스가 아니라, 할 일, 일정, 과제, 약속처럼 흩어져 있는 정보를 AI가 자동으로 정리해 사용자의 하루를 한눈에 보여준다는 콘셉트로 설계한 가상 생산성 앱 브랜드이다.

광고는 일정과 할 일이 동시에 쌓여 부담을 느끼는 **20~30대 취업준비생, 프리랜서, 직장인**을 주요 타겟으로 한다.  
짧은 러닝타임 안에서 “할 일 폭주”라는 문제 상황을 먼저 제시하고, MODU가 그 혼란을 정리해주는 해결 도구로 등장하는 구조를 사용한다.

이번 제작에서는 **Ideogram, ChatGPT 이미지 생성, KLING, Suno, CapCut TTS, CapCut**을 활용한다.  
이미지, 영상, 오디오, 내레이션, 편집 도구의 역할을 분리하고, 각 도구가 가진 장점을 활용하여 다음과 같은 제작 흐름을 설계한다.

> 기획 의도 정의 → 로고·앱 UI 기준 이미지 신규 생성 → 씬별 프롬프트 설계 → Ideogram·ChatGPT 이미지 생성 → KLING 영상 변환 → 오디오·내레이션 생성 → CapCut 통합 편집 → 최종 MP4 출력

이 프로젝트의 핵심은 단순히 여러 AI 도구를 사용하는 것이 아니라, **기획 의도와 브랜드 톤앤매너가 프롬프트를 거쳐 최종 영상으로 구현되는 제작 파이프라인을 설명할 수 있도록 문서화하는 것**이다.

---

## 2. 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| 브랜드명 | MODU |
| 브랜드 구분 | 과제 수행을 위해 기획한 가상 브랜드 |
| 발음 | 모두 |
| 제출자명 | 신의령 |
| 브랜드 유형 | 가상의 AI 일정·할 일 정리 플래너 앱 |
| 주요 타겟 | 할 일과 일정이 많은 20~30대 취업준비생, 프리랜서, 직장인 |
| 타겟 상황 | 공부, 지원서, 미팅, 약속, 개인 일정이 동시에 쌓여 무엇부터 해야 할지 헷갈리는 상황 |
| 톤앤매너 | 네온, 사이버펑크, 경쾌한 디지털 생산성 광고 |
| 시각 키워드 | 다크 네이비, 딥 퍼플, 네온 블루, 네온 핑크, 글로우, 카드형 UI |
| 앱 UI 기준 | `MODU` 영문 워드마크, `2026 7월`, `오늘`, 주간 캘린더, 네온 카드형 일정 리스트 |
| 대표 일정 라벨 | 기상 7:00, 아침 운동 8:00, 회의 9:00, 아침 식사 10:00 |
| 브랜드 성격 | 똑똑하지만 부담스럽지 않은 AI 비서, 할 일을 빠르게 정리해주는 친구 같은 앱 |
| USP | 흩어진 일정과 할 일을 AI가 자동으로 분류해 한눈에 보여준다. |
| 핵심 메시지 | 흩어진 할 일을 MODU가 모두 정리해준다. |
| 슬로건 | 할 일 폭주? MODU 정리해. |
| 엔딩 카피 | 나의 하루를 한눈에. |
| 내레이션 방향 | 발랄하고 경쾌한 20대 여성 목소리 |
| 광고 구조 | 할 일 폭주 → MODU 실행 → 일정 정리 → 브랜드 각인 |

---

## 3. 캠페인 목표 및 핵심 메시지

### 3-1. 캠페인 목표

| 구분 | 내용 |
|---|---|
| 광고 목적 | 브랜드 인지 및 앱 사용 관심 유도 |
| 광고 유형 | 10초 이내 숏폼형 브랜드 광고 |
| 전달 감정 | 복잡함에서 정리됨으로 바뀌는 시원함 |
| 기대 반응 | “내 할 일도 MODU로 정리하고 싶다”는 인상 형성 |
| 행동 유도 | 앱 이름과 핵심 기능을 기억하게 만들기 |

### 3-2. 핵심 메시지

> 흩어진 할 일을 MODU가 모두 정리해준다.

### 3-3. 메시지 구조

| 단계 | 내용 |
|---|---|
| 문제 제시 | 할 일, 일정, 알림이 동시에 쏟아져 사용자가 혼란을 느끼는 상황 |
| 전환 | MODU 앱이 실행되며 흩어진 정보가 한곳으로 모이기 시작 |
| 해결 | AI가 일정과 할 일을 카드 형태로 자동 정리 |
| 브랜드 각인 | MODU 로고, 슬로건, 엔딩 카피로 앱의 가치를 명확히 인식 |

---

## 4. 제작 파이프라인

본 광고는 AI 생성 결과물을 주된 소스로 사용하고, 편집 도구는 통합 편집 용도로만 사용한다.  
특히 영상 생성 도구는 크레딧 소모가 크기 때문에, 먼저 이미지 단계에서 구도와 스타일을 확정한 뒤 필요한 컷만 영상 변환을 시도한다.

| 단계 | 작업 내용 | 사용 도구 | 의사결정 이유 |
|---|---|---|---|
| 1단계 | 브랜드 콘셉트와 광고 메시지 정의 | ChatGPT, 수동 기획 | 영상 생성 전 메시지와 장면 구조를 고정하기 위해 사용 |
| 2단계 | MODU 로고와 앱 UI 기준 이미지 신규 생성 | Ideogram, ChatGPT 이미지 생성 | 가상 브랜드이므로 기존 소스 없이 브랜드 기준 비주얼을 먼저 확정하기 위해 사용 |
| 3단계 | 씬별 키비주얼 생성 및 정지 이미지를 짧은 모션 영상으로 변환 | Ideogram, ChatGPT 이미지 생성, KLING | 확정한 로고·앱 UI의 톤을 기준으로 씬 이미지를 만들고, 필요한 컷만 영상화해 크레딧을 절약 |
| 4단계 | BGM 생성 | Suno | 경쾌한 전자음악 기반의 짧은 광고 분위기 제작 |
| 5단계 | 내레이션 생성 | CapCut TTS | 10초 광고에 맞는 짧은 여성 음성 내레이션 제작 |
| 6단계 | 최종 통합 편집 | CapCut | 컷 편집, 자막, 로고 배치, 전환, 오디오 레벨 조정 |
| 7단계 | 최종 출력 및 검수 | CapCut | 10초 이내, 16:9, MP4, H.264/AAC 기준으로 출력 |

---

## 5. 사용 도구 목록

이번 프로젝트에서는 이미지, 비디오, 오디오, 음성, 편집 도구를 각각 분리해 사용한다.  
각 도구는 결과물의 역할에 따라 선택했으며, 도구의 대기열·크레딧·해상도 제한에 대비해 대체 도구도 함께 준비한다.

| 구분 | 실제 사용 도구 | 사용 목적 | 선택 이유 | 대체 도구 |
|---|---|---|---|---|
| 이미지 생성 | Ideogram, ChatGPT 이미지 생성 | MODU 로고, 앱 UI 기준 이미지, 씬별 키비주얼, 엔딩 이미지 신규 생성 | Ideogram으로 초기 로고·UI 기준 비주얼을 만들고, 크레딧 제한 또는 레퍼런스 고정이 필요한 장면은 ChatGPT 이미지 생성으로 보완한다. 공식 로고와 씬별 기준 이미지를 함께 첨부해 브랜드 연속성을 유지한다. | Google Whisk, Canva AI 이미지 생성 |
| 비디오 생성/변환 | KLING | Ideogram 또는 ChatGPT로 생성한 정지 이미지를 짧은 모션 영상으로 변환 | 이미지 기반 영상 변환과 짧은 광고 컷 제작에 적합하고, 네온 글로우·카메라 무빙·디지털 전환감을 구현하기 위해 사용 | CapCut 모션, Pika |
| 오디오 생성 | Suno | 10초 광고에 어울리는 경쾌한 디지털 BGM 생성 | 생산성 앱 광고에 맞는 밝고 에너지 있는 전자음악 분위기를 만들기 위해 사용 | CapCut 기본 오디오, Stable Audio, Beatoven |
| 음성 합성 | CapCut TTS | 발랄하고 경쾌한 20대 여성 톤의 내레이션 생성 | 최종 편집 도구와 바로 연결 가능하고, 짧은 광고 내레이션 제작이 간편하기 때문에 사용 | 클로바더빙, 타입캐스트 |
| 최종 편집 | CapCut | 컷 편집, 자막, 전환, 로고 삽입, 오디오 레벨 조정 | AI 생성 결과물을 하나의 10초 광고 영상으로 통합하기 위해 사용 | Canva Video, Premiere Pro |

---

## 6. 영상 제작 스펙

| 항목 | 기준 |
|---|---|
| 최종 영상 파일명 | `MODU_brand_ad_shinuiryeong.mp4` |
| 최종 영상 길이 | 10초 이내 |
| 화면 비율 | 16:9 |
| 목표 해상도 | 1080p, 1920x1080 |
| 대체 허용 조건 | 생성 도구의 크레딧, 대기열, 플랜 제한 또는 기기 성능 문제로 1080p 제작이 어려울 경우 720p 이상으로 제작 |
| 프레임레이트 | 24~30fps |
| 비디오 코덱 | H.264 |
| 오디오 코덱 | AAC |
| 필수 포함 요소 | AI로 생성한 시각 요소 + AI로 생성한 청각 요소 |
| 마지막 구간 조건 | 마지막 3초 구간에 브랜드명, 로고, 슬로건 또는 엔딩 카피 포함 |

### 6-1. 해상도 및 비율 통일 방침

최종 광고 영상은 과제의 최대 권장 스펙을 기준으로 **1080p, 1920x1080 해상도**를 목표로 제작한다.  
단, 영상 생성 도구의 무료 플랜 제한, 대기열 문제, 출력 해상도 제한이 발생할 경우 과제에서 허용한 기준에 따라 **720p 이상 해상도**로 제작한다.

모든 씬은 최종 편집 단계에서 **16:9 비율로 통일**한다.  
세로형 또는 정방형 이미지가 생성될 경우, CapCut에서 배경 블러, 크롭, 확대, 패닝을 활용해 화면 비율을 맞춘다.  
로고와 화면 카피는 영상 생성 과정에서 왜곡될 수 있으므로, 최종 엔딩 텍스트는 가능한 한 CapCut에서 직접 배치해 가독성을 확보한다.

---

## 7. 제작 전략

### 7-1. 기본 전략

이번 광고는 10초 이내의 짧은 브랜드 광고이므로, 많은 장면을 복잡하게 구성하기보다 **4개 씬 안에서 문제 제시와 해결 과정을 빠르게 보여주는 방식**으로 설계한다.

전체 영상은 다음 흐름을 따른다.

> 할 일 폭주 → MODU 실행 → 일정 자동 정리 → 브랜드 각인

### 7-2. 로고·앱 UI 신규 생성 전략

MODU는 과제 수행을 위해 기획한 가상 브랜드이므로 기존 로고와 앱 UI가 존재하지 않는다.  
따라서 본격적인 씬 제작에 들어가기 전, 먼저 **브랜드 기준 소스**를 새로 생성한다.

| 신규 생성 기준 소스 | 목적 | 파일명 | 제작 방식 |
|---|---|---|---|
| MODU 워드마크 로고 | 모든 씬과 엔딩 카드에서 반복 사용할 브랜드 기준 이미지 | `modu_logo_wordmark.png` | Ideogram에서 로고 전용 프롬프트로 생성 |
| MODU 앱 UI 기준 이미지 | 씬 2, 씬 3의 스마트폰 화면과 대시보드 스타일 기준 | `modu_app_ui_reference.png` | Ideogram에서 앱 대시보드 UI 프롬프트로 생성 |
| 브랜드 컬러 기준 | 전체 영상의 톤앤매너 통일 | 별도 파일 없음 | 다크 네이비, 딥 퍼플, 네온 블루, 네온 핑크를 모든 프롬프트에 반복 적용 |
| 씬 3 최종 프레임 또는 기준 이미지 | 씬 4 배경·중앙축·조명 연속성 기준 | `scene03_final_frame.png` | 씬 3 영상의 마지막 안정 프레임을 추출해 씬 4 엔딩 이미지 생성 시 공식 로고와 함께 첨부 |

로고와 앱 UI가 먼저 확정되어야 이후 씬 2, 씬 3, 씬 4의 스타일이 흔들리지 않는다.  
따라서 제작 순서는 **로고 생성 → 앱 UI 기준 이미지 생성 → 씬별 이미지 생성 → 영상 변환 → 편집** 순서로 진행한다.

#### MODU 로고 신규 생성 프롬프트

```text
clean futuristic wordmark logo for a virtual AI productivity planner app named MODU, modern sans-serif typography, sleek and minimal design, premium tech branding, subtle neon blue and neon pink glow accents, dark navy or deep purple background, the letter U subtly styled with a check mark or completion motif, digital and youthful mood, cyberpunk-inspired but clean and readable, centered composition, high contrast, professional logo presentation, no mockup hands, no extra objects, no long slogan
```

#### MODU 앱 UI 기준 이미지 신규 생성 프롬프트

아래 프롬프트는 MODU의 **앱 UI 기준 이미지**를 만들기 위한 최종 수정본이다.  
기존의 추상적인 “생산성 앱 대시보드” 표현에서 더 나아가, 실제 화면에 들어갈 날짜, 캘린더, 일정 카드, 한글 라벨, 하단 내비게이션까지 구체적으로 지정해 이후 씬 2와 씬 3의 기준 소스로 사용한다.

```text
full front view of a complete smartphone displaying a virtual AI productivity planner app UI named MODU, entire phone visible from top to bottom, entire app screen visible, not cropped, centered composition, straight-on view, no hands, no people, no extra objects.

Clean futuristic AI productivity planner app UI, dark navy and deep purple background, neon blue and neon pink highlights, cyberpunk-inspired but clean and readable, premium tech branding, minimal dashboard layout, high contrast, youthful digital mood, consistent with newly generated MODU logo and app UI style.

Keep the MODU wordmark exactly in English at the top header, glowing in neon blue and neon pink. The rest of the app interface should use clean readable Korean text. Show “2026 7월” and large title “오늘”. Add a weekly calendar row with Korean weekdays “월 화 수 목 금 토 일” and dates 4 to 10, with Saturday 9 highlighted in neon cyan.

Show four stacked schedule cards with clean icons, checklist circles, neon card borders, and short Korean labels only:
“기상” 7:00
“아침 운동” 8:00
“회의” 9:00
“아침 식사” 10:00

The meeting card is highlighted with a stronger neon blue and pink glow and small circular profile avatars. Bottom navigation bar with simple icons, glowing plus button in the center. Futuristic digital circuit board background outside the phone, purple glow on the left, blue glow on the right, subtle grid floor reflection, professional AI app brand advertisement style.

Negative prompt: cropped phone, cropped screen, cut off edges, side view, tilted angle, hands, fingers, people, extra objects, messy UI, overcrowded design, too much text, long Korean sentences, tiny text, unreadable text, garbled Korean, broken Korean characters, random letters, fake words, misspelled Korean, misspelled MODU, distorted MODU logo, wrong brand name, duplicate logo, blurry, low resolution, pixelated, distorted phone, warped screen, bad alignment, inconsistent icons, watermark, signature, artifacts, noisy image, amateur design.
```

#### 앱 UI 기준 이미지에서 반드시 확인할 요소

| 확인 항목 | 기준 |
|---|---|
| 스마트폰 구도 | 정면, 전체 기기 노출, 화면 잘림 없음 |
| 브랜드 표기 | 상단 헤더에 `MODU` 영문 워드마크가 정확히 표시 |
| 한글 UI | `2026 7월`, `오늘`, `월 화 수 목 금 토 일`, 일정 카드 4개가 읽을 수 있게 표시 |
| 일정 카드 | `기상 7:00`, `아침 운동 8:00`, `회의 9:00`, `아침 식사 10:00` |
| 강조 요소 | 토요일 9일은 네온 시안, 회의 카드는 네온 블루·핑크 글로우로 강조 |
| 배경 | 스마트폰 외부에 디지털 회로 보드, 좌측 퍼플 글로우, 우측 블루 글로우 |
| 불합격 기준 | MODU 오탈자, 깨진 한글, 잘린 스마트폰, 기울어진 구도, 너무 많은 텍스트 |


### 7-3. 크레딧 부족 및 도구 제한 대응 전략

영상 생성 도구는 크레딧 소모가 크고 무료 플랜에서는 대기열이나 해상도 제한이 발생할 수 있다. 따라서 다음 전략을 적용한다.

- 씬 수를 4개로 제한하여 재생성 횟수를 줄인다.
- 모든 씬을 영상 생성으로 만들기보다, 정지 이미지에 줌인·패닝·글리치 전환을 적용한다.
- 씬 1~3은 이미지 기반 모션을 적용하고, 씬 4는 씬 3의 배경과 중앙축을 유지한 로고 중심 엔딩 이미지를 생성한 뒤 최소한의 글로우·잔여 입자 모션만 적용한다.
- 동일한 네온 블루·네온 핑크·다크 네이비 배경 스타일을 반복 사용하여 브랜드 톤을 유지한다.
- KLING 사용이 어렵거나 크레딧이 부족할 경우 CapCut 모션을 대체 도구로 사용한다.
- 기존 MODU 로고와 앱 UI가 없으므로, 먼저 로고 1장과 앱 UI 1장을 신규 생성해 기준 비주얼로 확정한다.
- 앱 UI 기준 이미지는 `2026 7월`, `오늘`, 주간 캘린더, 4개 일정 카드가 보이는 화면으로 구체화해 실제 앱처럼 보이게 한다.
- 이후 씬 2~4에서는 새로 확정한 로고와 앱 UI의 색상, 형태, 일정 카드 스타일, 네온 강조 방식을 반복 사용해 브랜드 일관성을 유지한다.
- Ideogram 크레딧이 부족할 경우 공식 로고·UI 기준 이미지를 ChatGPT 이미지 생성에 첨부해 씬별 키비주얼을 보완하고, 추가 재생성이 어려운 장면은 CapCut 모션·배경·자막 조합으로 범위를 줄인다.
- 스타일 일관성이 필요한 경우 Google Whisk 또는 ChatGPT 이미지 생성에 새로 만든 MODU 로고/UI 이미지를 참조로 넣어 톤을 통일한다.
- 1080p 생성이 어려운 경우 과제 허용 기준에 따라 720p 이상으로 제작한다.

### 7-4. 스타일 일관성 유지 전략

MODU 광고는 로고, 앱 UI, 배경 그래픽이 서로 다른 스타일로 보이면 브랜드 경험이 약해질 수 있다.  
따라서 모든 이미지 프롬프트에는 다음 스타일 키워드를 반복적으로 사용한다.

- clean futuristic AI productivity planner app
- dark navy and deep purple background
- neon blue and neon pink highlights
- cyberpunk-inspired but clean and readable
- premium tech branding
- minimal dashboard layout
- high contrast
- youthful digital mood
- consistent with newly generated MODU logo and app UI style

앱 UI가 흔들리지 않도록 다음 정보도 고정한다.

- 상단 브랜드명은 `MODU` 영문 워드마크로 유지한다.
- 날짜 정보는 `2026 7월`, 메인 타이틀은 `오늘`로 유지한다.
- 주간 캘린더는 `월 화 수 목 금 토 일`과 4~10일 날짜 배열을 사용한다.
- 토요일 9일은 네온 시안 컬러로 강조한다.
- 일정 카드는 `기상`, `아침 운동`, `회의`, `아침 식사` 4개만 사용해 한글 깨짐 위험을 줄인다.

추가로 다음 원칙을 적용한다.

- 로고는 새로 생성한 뒤 한 번 확정하고, 이후 모든 씬과 엔딩에서 같은 로고 이미지를 반복 사용해 브랜드 일관성을 유지한다.
- 앱 UI는 같은 색상, 같은 카드형 레이아웃, 같은 배경 톤을 유지한다.
- 영상 변환 단계에서는 과도한 카메라 회전이나 인물 움직임을 피하고, 줌·패닝·글로우·글리치처럼 안정적인 모션을 중심으로 적용한다.
- 화면 안 텍스트가 깨질 경우, 해당 텍스트는 영상 생성 결과물 안에 넣지 않고 CapCut 자막으로 다시 배치한다.

---

## 8. 씬 구성 요약

| 씬 번호 | 길이 | 역할 | 핵심 내용 | 카피/내레이션 |
|---|---:|---|---|---|
| 씬 1 | 2초 | 문제 제시 | 네온 미래도시 감성이 들어간 바쁜 일상 혼란 장면 | 할 일이 너무 많아? |
| 씬 2 | 2초 | 전환 | 씬 1의 메모·종이·홀로그램 일정 조각이 로고만 표시된 스마트폰으로 빨려 들어감 | MODU가 모두 정리해. |
| 씬 3 | 3초 | 해결 | 씬 2에서 모인 디지털 입자가 고정된 MODU 최종 UI 안에서 일정 카드로 정리됨 | 일정, 과제, 약속까지 한눈에. |
| 씬 4 | 3초 | 브랜드 각인 | 씬 3의 스마트폰 위치와 회로 배경을 유지한 채 잔여 입자가 사라지고 공식 MODU 로고 엔딩 카드로 전환 | 나의 하루를 한눈에. |

총 길이: **10초**

---

## 9. 씬별 스토리보드 및 최종 프롬프트

본 섹션은 씬별 기획 내용과 이미지 생성 프롬프트, KLING 영상 변환 프롬프트를 함께 정리한 최종 제작 기준이다.  
전체 씬은 **다크 네이비, 딥 퍼플, 네온 블루, 네온 핑크, 미래도시적 분위기, 프리미엄 AI 생산성 앱 광고 톤**을 공통 기준으로 사용한다.

## 씬 1. 할 일 폭주 / 현실의 혼란

| 항목 | 내용 |
|---|---|
| 씬 번호 | 1 |
| 씬 길이 | 2초 |
| 목표 메시지 | 일상생활 속에서 여러 할 일과 준비물이 한꺼번에 몰려와 정신없는 문제 상황을 보여준다. |
| 화면 구성 | 바쁜 아침의 책상 또는 작은 방을 배경으로 노트북, 일정 메모, 커피컵, 공부 자료, 지원서 서류, 울리는 스마트폰, 가방, 시계, 택배 상자 등 여러 할 일을 상징하는 물건들이 한꺼번에 놓여 있다. 장면은 현실적인 일상 속 혼란을 보여주지만, 다크 네이비와 딥 퍼플 톤, 네온 블루와 핑크 조명, 미래도시적 반사광을 더해 MODU 브랜드의 사이버펑크 무드와 통일감을 유지한다. 앱 UI나 스마트폰 대시보드가 중심이 되지 않도록 한다. |
| 내레이션 또는 화면 카피 | 할 일이 너무 많아? |
| 사용 도구 및 목적 | Ideogram으로 현실적인 일상 속 할 일 폭주 키비주얼을 생성하고, KLING에서 짧은 줌인·흔들림·소품 움직임 모션을 적용한다. KLING 사용이 어렵거나 크레딧이 부족할 경우 CapCut 모션으로 대체한다. |
| 이미지 생성 프롬프트 원문 | chaotic everyday life scene for a 10-second commercial opening, showing a young adult overwhelmed by too many things to do, messy but visually appealing desk or compact room, laptop, planner, sticky notes, calendar page, coffee cup, study materials, resume papers, notebook, ringing smartphone, bag, clock, delivery box, to-do memo, multiple daily responsibilities all appearing at once, busy morning atmosphere, stressful and overwhelming mood, realistic daily life chaos, cinematic advertising composition, futuristic city-inspired mood, dark navy and deep purple environment, neon blue and neon pink lighting accents, subtle cyberpunk atmosphere, soft neon reflections, digital glow, premium tech brand aesthetic, high contrast, stylish and emotional commercial look, 16:9 composition, no app UI, no smartphone dashboard, no central interface, no clear human face, no brand logos, no readable long text. Negative prompt: app UI, smartphone app interface, clean dashboard, organized screen, centered phone mockup, futuristic app screen, readable interface text, tidy workspace, minimal composition, empty desk, plain office, bright natural daylight only, human face close-up, portrait shot, logo, watermark, signature, low resolution, blurry, distorted objects, random letters, garbled text, unrealistic anatomy |
| 영상 변환 프롬프트 원문 | 2-second commercial opening shot using the original image composition.Preserve the same person, face, body position, laptop, desk, room layout, lighting, and all existing objects. The overwhelmed person remains seated in the center, holding both sides of their head, with only subtle natural breathing and slight movement in the hair and clothes.Dozens of existing papers, sticky notes, document sheets, calendar pages, checklists, alarm icons, clock symbols, deadline markers, and translucent holographic task cards begin lifting from the cluttered room and swirling chaotically around the person. The tasks rotate, flutter, overlap, and fly past the foreground at different speeds, creating strong depth, parallax, and a feeling of mental overload. Some papers move rapidly across the camera, while sticky notes circle above the person’s head. Small glowing checklist icons, calendar symbols, notification badges, and deadline alerts appear between the floating documents. The movement should feel crowded, urgent, overwhelming, and slightly out of control, as if unfinished tasks are filling the entire room. Use a subtle cinematic push-in toward the person, combined with very slight handheld camera shake. The laptop and desk remain stable while nearby loose papers tremble and lift into the air. Neon blue and neon pink reflections pulse gently across the papers and the person’s face, maintaining the futuristic cyberpunk atmosphere. Fast energetic movement, busy morning tension, realistic paper physics, cinematic motion blur, strong foreground and background separation, premium commercial quality, dark navy, neon blue and neon pink lighting. Do not change the person’s identity or facial features. Do not move or deform the hands. Do not distort the laptop, desk, cups, clocks, or room. No new person, no face morphing, no extra limbs, no duplicated hands, no readable generated text, no app interface, no smartphone UI, no central dashboard, no camera rotation, no extreme zoom, no scene transition. |
| 출력 결과 요약 | 네온 블루·핑크 조명의 작업 공간에서 종이, 포스트잇, 홀로그램 카드가 인물 주변을 빠르게 떠다니는 영상 생성 완료. 원본 길이는 약 3.04초이며 최종 편집에서 핵심 구간 2초를 사용한다. |
| 생성 결과 파일명 또는 링크 | `scene01_task_overload.png` / `scene01_task_overload_motion.mp4` |

---

## 씬 2. MODU 실행 / 현실의 혼란을 앱으로 흡수

| 항목 | 내용 |
|---|---|
| 씬 번호 | 2 |
| 씬 길이 | 2초 |
| 목표 메시지 | MODU가 현실의 복잡한 할 일과 일정 조각을 한곳으로 모으기 시작하는 해결 도구임을 보여준다. |
| 화면 구성 | 씬 1 레퍼런스 이미지에 등장한 파란색·분홍색 종이, 노란 포스트잇, 청록색 반투명 홀로그램 카드, 체크리스트와 일정 조각이 동일한 색감과 깊이감을 유지한 채 스마트폰 주변에 떠 있다. 스마트폰은 화면 정중앙에 정면으로 나타나며, 화면에는 최종 일정 UI를 노출하지 않고 공식 `MODU` 로고와 중앙의 네온 흡수 지점만 표시한다. 일정 조각들은 곡선을 그리며 화면 안으로 빨려 들어가고 작은 디지털 입자로 변환된다. |
| 내레이션 또는 화면 카피 | MODU가 모두 정리해. |
| 사용 도구 및 목적 | Ideogram에 공식 MODU 로고 이미지와 씬 1 레퍼런스 이미지를 함께 첨부해 키비주얼을 생성한다. KLING에서는 종이·포스트잇·홀로그램 카드가 스마트폰으로 흡수되는 모션을 적용한다. |
| 로고 고정 원칙 | 첨부한 공식 MODU 로고를 최우선 기준으로 사용하고, 글자 형태·비율·자간·전체 인상을 새로 디자인하지 않는다. |
| UI 노출 원칙 | 씬 2에서는 최종 대시보드, 달력, 일정 카드, 하단 내비게이션을 보여주지 않는다. |
| 출력 결과 요약 | 종이·포스트잇·홀로그램 일정 조각이 스마트폰 화면의 네온 흡수 지점으로 빨려 들어가고 화면 내부에 청록색·분홍색 입자가 모이는 영상 생성 완료. 원본 길이는 8초이며 첫 번째 흡수 사이클 중 2초를 선별해 사용한다. |
| 생성 결과 파일명 또는 링크 | `scene02_modu_launch.png` / `scene02_modu_launch_motion.mp4` |

### 씬 2 참고 이미지 역할

| 우선순위 | 첨부 이미지 | 사용 목적 | 고정 범위 |
|---:|---|---|---|
| 1 | 공식 MODU 로고 이미지 | 브랜드 아이덴티티 고정 | 로고의 글자 형태, 비율, 자간, 색감, 전체 인상 |
| 2 | 씬 1 레퍼런스 이미지 | 시각적 연속성 유지 | 파란색·분홍색 종이, 노란 포스트잇, 청록색 홀로그램 카드, 네온 조명, 혼란스러운 깊이감 |
| 3 | MODU 앱 UI 기준 이미지(선택) | 색상과 앱 브랜드 분위기 참고 | 다크 네이비, 딥 퍼플, 네온 블루·핑크 스타일만 참고하며 최종 UI는 노출하지 않음 |

### 씬 2 로고 고정 프롬프트

```text
Use the attached official MODU logo image as the fixed brand identity reference. Preserve the logo very closely. Match the same wordmark shape, letterforms, spacing, proportions, color balance, and overall visual impression. Do not redesign, reinterpret, restyle, replace, or misspell the logo. Do not create a new logo. Reproduce the attached MODU logo as faithfully as possible and keep it clearly visible in the top header area of the smartphone screen.
```

### 씬 2 이미지 생성 프롬프트

```text
Use the attached reference images with clear and separate roles.

The official MODU logo image is the highest-priority fixed identity reference. Preserve this logo very closely. Match the same wordmark design, letter shapes, spacing, proportions, color balance, and overall neon branding impression. Do not redesign, reinterpret, restyle, replace, or misspell the logo.

The Scene 1 reference image is the visual continuity reference. Preserve its dark cluttered workspace atmosphere, deep navy and dark purple tones, neon blue and neon pink lighting, large blue and pink paper sheets, yellow sticky notes, translucent cyan holographic cards, checklist fragments, calendar-like fragments, glowing notification particles, cinematic motion-blur feeling, and layered chaotic depth.

If a MODU app UI reference image is attached, use it only as a secondary reference for the brand color palette and premium futuristic app mood. Do not reveal or recreate the final dashboard UI in this scene.

Create Scene 2 of the MODU commercial. Show a complete smartphone upright in the center of the frame, full front view, entire phone visible from top to bottom, straight-on angle, centered composition, clean premium advertisement style.

The smartphone appears as the solution inside the same visual world established in Scene 1. Surround the phone with the same types of floating elements from the Scene 1 reference: large blue and pink paper sheets, yellow sticky notes, translucent cyan holographic cards, checklist symbols, calendar fragments, document pieces, and glowing notification particles. Keep these elements at different foreground, middle-ground, and background depths.

The smartphone screen must remain mostly dark, glossy, and minimal. Do not show the final MODU dashboard or any completed app interface. Do not show a weekly calendar, schedule cards, checklist list, bottom navigation bar, finished Korean interface, or organized dashboard.

Place the official MODU logo from the attached logo reference clearly in the top header area of the smartphone screen. Keep enough clean space around the logo and do not allow floating objects to cover or distort it.

In the center of the dark smartphone screen, show a subtle circular digital intake point or abstract energy vortex glowing in neon blue and neon pink. The floating papers, sticky notes, checklist fragments, calendar pieces, holographic task cards, and notification particles curve toward this point as if they are being magnetically absorbed into the MODU app.

The scene should communicate the exact transition from everyday chaos into digital organization. The outer edges may retain faint traces of the cluttered room, while the area around the smartphone gradually becomes a clean futuristic digital environment with dark circuit-board patterns, purple glow on the left, blue glow on the right, and subtle reflective grid accents.

Premium AI productivity app advertisement style, cinematic depth, high contrast, strong foreground and background separation, youthful digital mood, subtle cyberpunk atmosphere, clean central focus.

Negative prompt: redesigned logo, altered logo, fake MODU logo, misspelled MODU, different wordmark, duplicate logo, random English text, random Korean text, final dashboard UI, completed app interface, weekly calendar, schedule cards, bottom navigation, finished Korean dashboard, different app design, cropped phone, cut-off screen, side view, tilted angle, hands, fingers, extra people, face close-up, futuristic city skyline, watermark, signature, blurry image, low resolution, warped screen, distorted objects, unreadable text.
```

### 씬 2 영상 변환 프롬프트

```text
2-second commercial transition shot based on the generated Scene 2 image.

Keep the complete smartphone centered, upright, fully visible, and straight-on. Preserve the official MODU logo exactly as shown in the source image. Keep the logo stable, readable, unobstructed, and unchanged throughout the shot.

The phone screen remains dark and glossy with no completed dashboard. Show only the fixed MODU logo at the top and a subtle circular neon blue and pink digital intake point in the center.

The large blue and pink paper sheets, yellow sticky notes, translucent cyan holographic cards, checklist fragments, calendar pieces, document fragments, and glowing notification particles begin with chaotic floating movement around the phone. Their paths gradually bend into smooth curved streams toward the center of the smartphone screen.

As each element approaches the screen, it transforms into tiny neon cyan and pink digital particles and is absorbed into the glowing intake point. Preserve realistic paper flutter, layered depth, foreground parallax, soft cinematic motion blur, and the neon blue and pink lighting from Scene 1.

By the final moment, most of the floating task elements have entered the phone. Leave a concentrated cluster of cyan and pink particles inside the dark screen, ready to form the final interface in Scene 3.

Do not reveal the final dashboard. No calendar UI, no schedule cards, no bottom navigation, no finished Korean interface, no new app design, no logo redesign, no misspelled MODU, no camera rotation, no extreme zoom, no warped screen, no random text, no abrupt disappearance of objects.
```

---

## 씬 3. 일정 자동 정리 / 고정된 MODU 최종 UI 공개

| 항목 | 내용 |
|---|---|
| 씬 번호 | 3 |
| 씬 길이 | 3초 |
| 목표 메시지 | 씬 2에서 모인 일정과 할 일이 MODU의 카드형 대시보드에 자동으로 정리되어 한눈에 보인다는 기능적 가치를 전달한다. |
| 화면 구성 | 스마트폰 전체가 정면으로 보이고, 공식 `MODU` 로고와 확정된 앱 UI 기준 이미지의 레이아웃을 최대한 그대로 유지한다. 화면에는 `2026 7월`, 큰 제목 `오늘`, 주간 캘린더 `월 화 수 목 금 토 일`, 날짜 4~10, 토요일 9일 강조, 네 개의 일정 카드가 표시된다. 씬 2에서 흡수된 청록색·분홍색 디지털 입자는 텍스트를 새로 만들지 않고 카드 테두리·체크 원·아이콘·글로우로 정착한다. |
| 내레이션 또는 화면 카피 | 일정, 과제, 약속까지 한눈에. |
| 사용 도구 및 목적 | ChatGPT 이미지 생성 또는 Ideogram에서 공식 MODU 로고와 최종 앱 UI 기준 이미지를 함께 첨부해 고정된 대시보드 키비주얼을 생성한다. KLING에서는 UI를 다시 설계하지 않고 카드 글로우, 체크 활성화, 플러스 버튼 펄스와 디지털 입자 정착 모션만 적용한다. |
| 로고 고정 원칙 | 공식 MODU 로고의 글자 형태, 자간, 비율, 색감과 전체 인상을 유지한다. |
| UI 고정 원칙 | 앱 UI 기준 이미지를 고정 템플릿으로 사용하며, 캘린더·일정 카드·하단 내비게이션의 위치와 구조를 새로 디자인하지 않는다. |
| 출력 결과 요약 | 완성된 MODU UI를 유지한 채 디지털 입자와 네온 빛이 캘린더·일정 카드·플러스 버튼을 활성화하는 영상 생성 완료. 원본 길이는 약 4.01초이며 최종 편집에서 UI가 안정적으로 보이는 3초를 사용한다. |
| 생성 결과 파일명 또는 링크 | `scene03_organized_dashboard.png` / `scene03_organized_dashboard_motion.mp4` |

### 씬 3 참고 이미지 역할

| 우선순위 | 첨부 이미지 | 사용 목적 | 고정 범위 |
|---:|---|---|---|
| 1 | 공식 MODU 로고 이미지 | 브랜드 아이덴티티 고정 | 로고 글자 형태, 비율, 자간, 색감, 전체 인상 |
| 2 | MODU 앱 UI 기준 이미지 | 최종 대시보드 고정 | 스마트폰 구도, 헤더, 날짜, 주간 캘린더, 일정 카드, 강조 요소, 하단 내비게이션 |
| 3 | 씬 2 결과 이미지(선택) | 장면 연결 참고 | 화면 안에 모여 있는 청록색·분홍색 디지털 입자와 네온 흡수 효과 |

### 씬 3 로고 고정 프롬프트

```text
Use the attached official MODU logo image as the fixed brand identity reference. Preserve the logo very closely. Match the same wordmark shape, letterforms, spacing, proportions, color balance, and overall visual impression. Do not redesign, reinterpret, restyle, replace, or misspell the logo. Do not create a new logo.
```

### 씬 3 UI 고정 프롬프트

```text
Use the attached MODU app UI reference image as the fixed final interface template. Preserve the complete smartphone presentation and the app layout as closely as possible. Keep the same top MODU header, the same “2026 7월” label, the same large “오늘” title, the same weekly calendar row with “월 화 수 목 금 토 일” and dates 4 to 10, the same neon cyan highlight on Saturday 9, the same four stacked schedule cards, the same highlighted meeting card, and the same bottom navigation bar with the glowing plus button. Do not redesign, rearrange, simplify, replace, or invent a different app interface.
```

### 씬 3 이미지 생성 프롬프트

```text
Use the attached reference images with clear and separate roles.

The official MODU logo image is the fixed brand identity reference. Preserve the logo very closely. Match the same wordmark design, letter shapes, spacing, proportions, color balance, and overall neon branding impression. Do not redesign, reinterpret, restyle, replace, or misspell the logo.

The MODU app UI reference image is the fixed final interface template. Preserve the complete smartphone presentation, straight-on angle, centered composition, dark navy and deep purple interface, neon blue and neon pink accents, premium futuristic branding, and clean cyberpunk-inspired but readable design language.

Create Scene 3 of the MODU commercial. Show the complete smartphone in a full front view, entire phone visible from top to bottom, entire screen visible, not cropped, straight-on angle, centered composition.

Preserve the final MODU app layout as closely as possible. Keep the official MODU logo at the top header. Show “2026 7월” and a large title “오늘”. Keep the weekly calendar row with Korean weekdays “월 화 수 목 금 토 일” and dates 4 to 10, with Saturday 9 highlighted in neon cyan.

Keep the same four stacked schedule cards with clean icons, checklist circles, neon card borders, and the following short Korean labels:
“기상” 7:00
“아침 운동” 8:00
“회의” 9:00
“아침 식사” 10:00

Keep the “회의” card highlighted with a stronger neon blue and neon pink glow and small circular profile avatars. Preserve the bottom navigation bar with simple icons and the glowing plus button in the center.

To connect with Scene 2, include subtle traces of concentrated neon cyan and pink digital particles inside the screen. These particles should appear to finish forming the card borders, checklist circles, icons, and glow effects. Do not use the particles to rewrite, replace, or distort the existing Korean text or MODU logo.

Outside the smartphone, preserve the futuristic digital circuit-board environment with purple glow on the left, blue glow on the right, and subtle reflective grid floor accents. Premium AI productivity app advertisement style, polished final reveal, high contrast, clean centered composition, balanced spacing, youthful digital mood.

Negative prompt: redesigned logo, altered logo, fake MODU logo, misspelled MODU, different wordmark, different app design, different layout, rearranged calendar, missing calendar row, missing schedule cards, missing bottom navigation, random English text, random Korean text, garbled Korean, broken Korean characters, fake words, tiny unreadable text, cropped phone, cut-off screen, side view, tilted angle, hands, fingers, extra people, cluttered interface, warped screen, distorted icons, watermark, signature, blurry image, low resolution.
```

### 씬 3 영상 변환 프롬프트

```text
3-second final MODU UI activation and reveal shot based on the supplied Scene 3 image.

Continue visually from the final state of Scene 2, where a concentrated cluster of neon cyan and pink digital particles remains in the center of the smartphone screen.

Keep the complete smartphone centered, fully visible, upright, and straight-on. Preserve the official MODU logo, all Korean UI text, weekly calendar, dates, schedule card positions, icons, profile avatars, and bottom navigation exactly as shown in the source image. Do not rewrite, regenerate, rearrange, replace, or redesign any interface element.

The complete MODU dashboard already exists in the source image and must remain structurally unchanged. At the beginning, keep the interface slightly dim while a compact cyan and pink particle cluster glows softly near the center of the screen.

The particle cluster gently contracts and releases a soft neon pulse across the existing interface. Do not build the UI from an empty screen. Instead, use the particles only to activate and illuminate the existing UI.

First, a subtle neon light travels across the weekly calendar and reinforces the cyan highlight around Saturday 9. Next, the light moves downward and softly illuminates the existing schedule card borders one by one in order: “기상”, “아침 운동”, “회의”, and “아침 식사”.

The checklist circles activate gently without changing their shapes or positions. The “회의” card receives the strongest neon blue and pink glow, while its Korean text and circular profile avatars remain perfectly stable.

After the schedule cards activate, the bottom center plus button gently pulses once. End with the complete MODU dashboard clearly visible, stable, readable, and fully organized.

Use subtle glow animation, smooth light movement, minimal camera motion, and a polished premium AI productivity app commercial finish.

No new text, no interface reconstruction, no logo redesign, no misspelled MODU, no Korean text distortion, no changed dates, no new schedule cards, no rearranged layout, no moving avatars, no camera rotation, no extreme zoom, no warped phone, no warped screen, no extra objects.
```

---

## 씬 4. 브랜드 각인 / 씬 3에서 이어지는 엔딩 카드

| 항목 | 내용 |
|---|---|
| 씬 번호 | 4 |
| 씬 길이 | 3초 |
| 목표 메시지 | MODU 앱이 하루 일정을 정리한 결과를 브랜드 로고와 엔딩 카피로 연결해 브랜드명을 명확히 각인한다. |
| 화면 구성 | 씬 3 마지막 화면과 동일한 16:9 중앙축, 다크 네이비·딥 퍼플 회로 보드 배경, 왼쪽 퍼플 글로우, 오른쪽 블루 글로우, 네온 그리드 바닥을 유지한다. 씬 3에서 스마트폰이 있던 중앙 위치에는 공식 `MODU` 워드마크가 크게 배치된다. 스마트폰 전체와 앱 UI는 더 이상 보이지 않으며, 스마트폰이 사라진 자리에는 매우 옅은 폰 형태의 네온 잔광과 청록색·분홍색 입자 흔적만 남겨 씬 3에서 자연스럽게 전환된 느낌을 만든다. |
| 내레이션 또는 화면 카피 | 나의 하루를 한눈에. |
| 사용 도구 및 목적 | 공식 MODU 로고 이미지와 씬 3 영상의 마지막 안정 프레임을 ChatGPT 이미지 생성 또는 Ideogram에 함께 첨부해 엔딩 키비주얼을 생성한다. KLING에서는 로고 자체를 다시 만들지 않고 잔여 폰 아우라가 사라지는 효과, 소량의 디지털 입자 이동, 로고 전체의 한 번의 글로우 펄스만 적용한다. 한글 슬로건과 엔딩 카피는 CapCut에서 직접 입력한다. |
| 로고 고정 원칙 | 공식 MODU 로고를 최우선 고정 기준으로 사용하며, 글자 형태·비율·자간·색상 균형을 새로 디자인하거나 변형하지 않는다. |
| 배경 연속성 원칙 | 씬 3의 회로 보드 배경과 좌우 퍼플·블루 조명, 중앙 스마트폰 위치를 그대로 유지하고 미래도시 빌딩이나 다른 환경으로 교체하지 않는다. |
| 텍스트 처리 원칙 | 생성 이미지에는 한글 슬로건이나 임의 문자를 넣지 않고, `할 일 폭주? MODU 정리해.`와 `나의 하루를 한눈에.`는 CapCut에서 직접 배치한다. |
| 출력 결과 요약 | 씬 3의 스마트폰과 완성 UI가 사라진 중앙 위치에 공식 MODU 로고가 남고, 동일한 회로 보드 배경과 잔여 입자 효과를 유지하는 프리미엄 엔딩 카드 확보 예정 |
| 생성 결과 파일명 또는 링크 | `scene04_modu_endcard.png` / `scene04_modu_endcard_motion.mp4` |

### 씬 4 참고 이미지 역할

| 우선순위 | 첨부 이미지 | 사용 목적 | 고정 범위 |
|---:|---|---|---|
| 1 | 공식 MODU 로고 이미지 | 브랜드 아이덴티티 고정 | 워드마크 글자 형태, 자간, 비율, 색감, 전체 인상 |
| 2 | 씬 3 마지막 안정 프레임 또는 앱 UI 기준 이미지 | 장면 연속성 고정 | 16:9 구도, 중앙축, 회로 보드 패턴, 왼쪽 퍼플·오른쪽 블루 조명, 그리드 바닥 |
| 3 | 씬 3 영상 몽타주 또는 결과 이미지(선택) | 전환 효과 참고 | 스마트폰 위치, 청록색·분홍색 잔여 입자, 네온 글로우 강도 |

### 씬 4 로고 고정 프롬프트

```text
Use the attached official MODU logo image as the highest-priority fixed brand identity reference. Preserve the logo very closely. Match the same wordmark shape, letterforms, spacing, proportions, color balance, and overall visual impression. Do not redesign, reinterpret, restyle, replace, recolor, or misspell the logo. Do not create a new logo. Reproduce the attached MODU logo as faithfully as possible.
```

### 씬 4 이미지 생성 프롬프트

```text
Use the attached reference images with clear and separate roles.

The official MODU logo image is the highest-priority fixed brand identity reference. Preserve the logo very closely. Match the same wordmark shape, letterforms, spacing, proportions, color balance, and overall visual impression. Do not redesign, reinterpret, restyle, replace, recolor, or misspell the logo. Do not create a new logo.

The Scene 3 final-frame reference is the fixed visual continuity reference. Preserve its 16:9 composition, symmetrical centered framing, dark navy and deep purple digital environment, circuit-board patterns, purple neon glow on the left, blue neon glow on the right, and reflective grid floor. Do not replace this background with a futuristic city, buildings, a different room, or another environment.

Create Scene 4, the final premium brand end card for the MODU AI productivity planner app.

Place the official MODU wordmark prominently in the exact center of the frame, positioned where the smartphone stood in Scene 3. The logo should be large, sharp, clearly readable, and visually faithful to the attached official logo reference. Keep clean negative space around the complete wordmark.

The smartphone and completed dashboard from Scene 3 are no longer fully visible. Include only a very subtle vertical trail of neon cyan and pink digital particles, soft residual light, and a faint abstract phone-shaped aura behind the logo. This residual aura should suggest that the smartphone has smoothly dissolved into the MODU brand identity, but it must not look like a complete smartphone, readable app interface, second logo, or additional object.

Keep the transition traces restrained and elegant. Use only a small amount of residual cyan and pink particles gently fading around the logo. Do not create another large particle explosion. The final scene should feel calm, organized, complete, and premium after the energetic Scene 3 activation.

Preserve the same digital circuit-board background from Scene 3, with purple glow on the left, blue glow on the right, subtle reflective grid floor, high contrast, clean symmetry, premium futuristic technology branding, and polished cyberpunk-inspired advertisement style.

Leave a clean and visually balanced empty area below the MODU logo for Korean slogan and ending copy to be added later in CapCut. Do not generate Korean text, an English slogan, random letters, extra brand names, or interface text inside the image.

16:9 composition, professional AI productivity app advertisement end card, clean central focus, subtle neon atmosphere, premium final reveal.

Negative prompt: redesigned MODU logo, altered wordmark, misspelled MODU, duplicate logo, new logo design, random text, Korean text, English slogan, readable app UI, calendar, schedule cards, bottom navigation, complete smartphone, large phone mockup, futuristic city skyline, buildings, different background, excessive particle explosion, cluttered composition, extra objects, people, hands, watermark, signature, blurry image, low resolution, distorted letters, warped logo, noisy background.
```

### 씬 4 영상 변환 프롬프트

```text
3-second premium MODU brand end-card animation based on the generated Scene 4 image.

Maintain the exact same dark circuit-board background, purple glow on the left, blue glow on the right, reflective grid floor, and centered symmetrical composition established in Scene 3.

Keep the official MODU logo already visible, centered, sharp, readable, and structurally unchanged throughout the entire shot. Do not form, rewrite, regenerate, reshape, recolor, separate, or animate the individual letters.

At the beginning, preserve a faint residual phone-shaped neon aura and a small amount of cyan and pink digital particles behind and around the fixed logo, continuing from the smartphone position in Scene 3.

The residual phone-shaped aura slowly fades and dissolves. The small cyan and pink particles drift gently inward and disappear around the logo without covering, touching, rebuilding, or distorting the wordmark.

After the aura has faded, add one subtle neon blue and pink glow pulse around the complete fixed MODU wordmark. Keep the movement minimal, elegant, calm, and premium. Leave the area below the logo clean and empty for Korean slogan and ending copy to be added later in CapCut.

End with the official MODU logo completely stable and readable against the same circuit-board background.

No new text, no Korean text, no slogan generation, no logo redesign, no misspelled MODU, no duplicate logo, no readable smartphone UI, no schedule cards, no calendar, no city skyline, no large particle explosion, no camera rotation, no extreme zoom, no warped logo, no extra objects.
```

### 씬 3 → 씬 4 연결 편집 기준

| 구간 | 권장 연출 |
|---|---|
| 씬 3 마지막 | 완성된 MODU UI와 스마트폰이 중앙에서 안정적으로 보이는 프레임으로 종료 |
| 전환 길이 | 약 0.15~0.25초 |
| 전환 효과 | 짧은 네온 시안·화이트 플래시 또는 소량의 입자 디졸브 |
| 위치 맞춤 | 씬 3 스마트폰 중심과 씬 4 MODU 로고 중심을 같은 좌표에 배치 |
| 배경 맞춤 | 회로 패턴, 좌측 퍼플·우측 블루 글로우, 그리드 바닥의 크기와 밝기를 최대한 동일하게 유지 |
| 오디오 연결 | 씬 3 체크 완료음 이후 짧은 디지털 수렴음 또는 부드러운 브랜드 차임 삽입 |

### CapCut에서 직접 넣을 문구

```text
할 일 폭주? MODU 정리해.
나의 하루를 한눈에.
```

권장 배치는 첫 번째 줄을 로고 아래에 슬로건으로 표시하고, 두 번째 줄을 더 작은 크기의 엔딩 카피로 배치하는 방식이다. 한글 문구는 생성 이미지에 포함하지 않고 CapCut에서 직접 입력해 가독성과 철자 정확성을 확보한다.

---

## 10. 프롬프트 수정 전/후 기록

## 씬 1 프롬프트 개선 로그

### 10-1. 수정 전 의도

초기 씬 1은 사용자가 할 일과 일정에 압도되는 상황을 보여주기 위해, 디지털 할 일 카드와 알림창이 화면에 떠다니는 장면으로 구상하였다.  
하지만 이 방식은 씬 2와 씬 3에서 등장하는 MODU 앱 UI 장면과 시각적 역할이 겹칠 수 있었다.

### 10-2. 수정 전 프롬프트

```text
chaotic digital task overload scene for a virtual AI productivity planner app advertisement, many floating schedule cards, calendar reminders, notification popups, checklist icons, short readable Korean labels, dark navy and deep purple background, neon blue and neon pink highlights, cyberpunk-inspired but clean and readable, 16:9 composition
```

### 10-3. 발생한 문제

- 씬 1부터 앱 UI와 유사한 디지털 카드가 등장해, 문제 제시 장면과 해결 장면의 차이가 약해질 수 있었다.
- 씬 2의 “MODU 앱 실행” 장면, 씬 3의 “정리된 앱 UI” 장면과 화면 요소가 겹쳐 광고의 기승전결이 흐려질 수 있었다.
- 현실에서 할 일이 많아 정신없는 상황에 대한 공감이 약해질 수 있었다.

### 10-4. 수정 방향

씬 1은 앱 UI가 아니라 **현실의 혼란**을 보여주는 방향으로 수정하였다.  
다만 MODU 광고 전체의 브랜드 통일성을 유지하기 위해 현실적인 책상·방 장면에 다크 네이비, 딥 퍼플, 네온 블루, 네온 핑크 조명과 미래도시적 반사광을 적용하였다.

### 10-5. 수정 후 프롬프트

```text
chaotic everyday life scene for a 10-second commercial opening, showing a young adult overwhelmed by too many things to do, messy but visually appealing desk or compact room, laptop, planner, sticky notes, calendar page, coffee cup, study materials, resume papers, notebook, ringing smartphone, bag, clock, delivery box, to-do memo, multiple daily responsibilities all appearing at once, busy morning atmosphere, stressful and overwhelming mood, realistic daily life chaos, cinematic advertising composition, futuristic city-inspired mood, dark navy and deep purple environment, neon blue and neon pink lighting accents, subtle cyberpunk atmosphere, soft neon reflections, digital glow, premium tech brand aesthetic, high contrast, stylish and emotional commercial look, 16:9 composition, no app UI, no smartphone dashboard, no central interface, no clear human face, no brand logos, no readable long text
```

### 10-6. 결과 변화

수정 후 씬 1은 MODU 앱 화면을 직접 보여주기보다, MODU가 필요한 현실적 문제 상황을 먼저 보여주는 장면으로 바뀌었다.  
이를 통해 씬 1은 “복잡한 일상”, 씬 2는 “MODU로 전환”, 씬 3은 “정리된 하루”, 씬 4는 “브랜드 각인”이라는 구조가 더 명확해졌다.

### 추가 개선 판단

텍스트와 로고는 이미지·영상 생성 과정에서 왜곡될 수 있으므로, 최종 엔딩 구간의 한글 슬로건과 엔딩 카피는 CapCut에서 직접 배치한다.  
영상 생성/변환은 KLING을 사용하되, 자막·오디오·로고 오버레이·최종 컷 편집은 CapCut에서 진행해 과제의 통합 편집 범위 안에서 완성도를 높인다.

---

## 11. 오디오 기획

| 항목 | 내용 |
|---|---|
| BGM 생성 도구 | Suno |
| 음성 합성 도구 | CapCut TTS |
| BGM 방향 | 빠르고 경쾌한 디지털 팝 또는 일렉트로닉 비트 |
| 분위기 | 통통 튀고 생산적인 느낌, 복잡함이 정리되는 시원한 분위기 |
| 효과음 | 필요 시 CapCut에서 알림음, 글리치 전환음, 정리 완료 체크 사운드 추가 |
| 내레이션 톤 | 발랄하고 경쾌한 20대 여성 목소리 |
| 내레이션 문장 | 할 일이 너무 많아? MODU가 모두 정리해. 일정, 과제, 약속까지 한눈에. 나의 하루를 한눈에. |

### 11-1. Suno BGM 생성 프롬프트

```text
upbeat futuristic electronic pop background music for a 10-second AI productivity app advertisement, bright digital synth, playful rhythm, clean tech mood, energetic but not aggressive, suitable for a young female voice-over, short commercial jingle, no lyrics
```

### 11-2. CapCut TTS 내레이션 스크립트

```text
할 일이 너무 많아?
MODU가 모두 정리해.
일정, 과제, 약속까지 한눈에.
나의 하루를 한눈에.
```

### 11-3. 오디오 믹싱 방침

- 내레이션이 가장 잘 들리도록 BGM 볼륨은 낮게 배치한다.
- 씬 1에서는 알림음, 진동음, 종이 넘기는 소리 같은 짧은 효과음을 사용해 현실적인 혼란감을 만든다.
- 씬 2에서는 전환음 또는 네온 플래시 효과음을 넣어 앱 실행감을 강조한다.
- 씬 3에서는 체크 완료 효과음을 넣어 “정리됨”의 감각을 전달한다.
- 씬 4에서는 씬 3의 체크 완료음 뒤에 짧은 디지털 수렴음 또는 브랜드 차임을 넣고, BGM을 자연스럽게 마무리해 로고와 엔딩 카피 인지가 가능하도록 음량을 안정시킨다.

---

## 12. KLING 영상 변환 및 최종 편집 계획

영상 생성/변환은 **KLING**에서 진행하고, 최종 통합 편집은 **CapCut**에서 진행한다.  
KLING은 정지 이미지를 짧은 모션 영상으로 변환하는 용도로 사용하고, CapCut은 컷 편집, 자막, 로고 오버레이, 오디오 레벨 조정 등 통합 편집 용도로 사용한다.

### 편집 순서

1. 씬별 이미지 또는 영상 파일을 16:9 타임라인에 배치한다.
2. 생성 원본의 길이와 관계없이 최종 타임라인에서는 씬 1·2·3·4를 각각 2초, 2초, 3초, 3초로 조정한다.
3. 씬 1에는 빠른 줌인 또는 흔들림 효과를 적용해 할 일 폭주 느낌을 준다.
4. 씬 2에는 씬 1의 종이·포스트잇·홀로그램 카드가 스마트폰 중앙의 네온 흡수 지점으로 빨려 들어가는 모션을 적용하며, 최종 UI는 노출하지 않는다.
5. 씬 3에는 고정된 MODU UI를 유지한 상태에서 디지털 입자가 카드 테두리와 체크 원에 정착하고, 일정 카드가 순서대로 빛나는 모션을 적용한다.
6. 씬 4에는 씬 3과 동일한 배경·중앙축을 유지하고, 잔여 폰 아우라와 소량의 입자가 사라진 뒤 고정된 공식 MODU 로고에 한 번의 네온 글로우 펄스를 적용한다. 슬로건과 엔딩 카피는 CapCut에서 순차적으로 배치한다.
7. Suno로 생성한 BGM과 CapCut TTS로 만든 내레이션을 삽입하고, 음량을 조정한다.
8. 최종 파일을 MP4 형식으로 출력한다.
9. 가능하면 1080p로 인코딩하고, 도구 제한이 있을 경우 720p 이상으로 출력한다.


### 현재 생성 영상 길이 검토

| 생성 파일 | 확인된 원본 길이 | 최종 사용 길이 | 편집 기준 |
|---|---:|---:|---|
| `scene01_task_overload_motion.mp4` | 약 3.04초 | 2초 | 인물 주변의 종이와 홀로그램 카드가 가장 역동적으로 떠다니는 구간 사용 |
| `scene02_modu_launch_motion.mp4` | 8.00초 | 2초 | 첫 번째 흡수 사이클에서 종이·카드가 스마트폰으로 모이고 입자 덩어리가 형성되는 구간 사용 |
| `scene03_organized_dashboard_motion.mp4` | 약 4.01초 | 3초 | UI가 변형되지 않고 캘린더·일정 카드·플러스 버튼이 안정적으로 활성화되는 구간 사용 |
| `scene04_modu_endcard_motion.mp4` | 생성 예정 | 3초 | 잔여 폰 아우라 소멸 → 공식 로고 글로우 → 엔딩 카피 고정 순서로 사용 |

원본 영상을 단순히 처음부터 자르기보다, 각 장면의 핵심 동작과 마지막 안정 프레임을 기준으로 인·아웃 지점을 지정한다. 씬 2는 입자가 화면 중앙에 모인 상태에서 종료하고, 씬 3은 스마트폰과 UI가 완전히 안정된 상태에서 종료해야 다음 장면과 자연스럽게 연결된다.

---

## 13. 최종 영상 구성 타임라인

| 시간 | 화면 | 오디오/내레이션 | 편집 포인트 |
|---|---|---|---|
| 0:00~0:02 | 할 일 카드와 알림이 폭주하는 네온 화면 | 할 일이 너무 많아? | 빠른 줌인, 알림 효과음 |
| 0:02~0:04 | 씬 1의 종이·포스트잇·홀로그램 카드가 공식 MODU 로고가 표시된 스마트폰의 네온 흡수 지점으로 빨려 들어감 | MODU가 모두 정리해. | 곡선 흡수 모션, 디지털 입자 변환, 최종 UI 비노출 |
| 0:04~0:07 | 씬 2에서 모인 입자가 고정된 MODU 앱 UI 안에서 캘린더·카드 테두리·체크 요소로 정착 | 일정, 과제, 약속까지 한눈에. | 카드 글로우 순차 활성화, 회의 카드 강조, 체크 사운드 |
| 0:07~0:10 | 씬 3의 스마트폰 위치에서 잔여 폰 아우라와 입자가 사라지고 공식 MODU 로고 엔딩 카드로 전환 | 나의 하루를 한눈에. | 0.15~0.25초 네온 플래시 또는 입자 디졸브, 로고 1회 글로우, 슬로건·엔딩 카피 순차 등장 |

---

## 14. 최종 결과 파일명 규칙

| 파일 종류 | 파일명 |
|---|---|
| 스토리보드 MD 문서 | `MODU_storyboard_shinuiryeong.md` |
| 스토리보드 PDF 문서 | `MODU_storyboard_shinuiryeong.pdf` |
| MODU 로고 기준 이미지 | `modu_logo_wordmark.png` |
| MODU 앱 UI 기준 이미지 | `modu_app_ui_reference.png` |
| 최종 광고 영상 | `MODU_brand_ad_shinuiryeong.mp4` |
| 씬 1 이미지 | `scene01_task_overload.png` |
| 씬 1 영상 | `scene01_task_overload_motion.mp4` |
| 씬 2 이미지 | `scene02_modu_launch.png` |
| 씬 2 영상 | `scene02_modu_launch_motion.mp4` |
| 씬 3 이미지 | `scene03_organized_dashboard.png` |
| 씬 3 영상 | `scene03_organized_dashboard_motion.mp4` |
| 씬 4 이미지 | `scene04_modu_endcard.png` |
| 씬 4 영상 | `scene04_modu_endcard_motion.mp4` |
| BGM 파일 | `modu_bgm_electronic_pop.wav` |
| 내레이션 파일 | `modu_voiceover_young_female.wav` |
| 최종 편집 프로젝트 | `MODU_capcut_project` |

---

## 15. 제작 의사결정 요약

MODU 광고는 짧은 시간 안에 앱의 핵심 가치를 전달해야 하므로, 복잡한 캐릭터 서사보다 **할 일 폭주에서 정리로 바뀌는 화면 변화**를 중심으로 기획하였다.  
브랜드의 핵심 메시지인 “흩어진 할 일을 MODU가 모두 정리해준다”를 시각적으로 보여주기 위해, 씬 1에서는 바쁜 일상 속 여러 준비물과 일정이 한꺼번에 몰린 현실적인 혼란 장면을 제시한다. 씬 2에서는 동일한 종이·포스트잇·홀로그램 일정 조각이 공식 MODU 로고만 표시된 스마트폰으로 흡수되고, 씬 3에서는 수집된 디지털 입자가 고정된 카드형 대시보드 안에서 정리된 결과를 보여준다. 씬 4에서는 씬 3과 동일한 회로 보드 배경과 중앙축을 유지한 채 스마트폰의 잔여 아우라가 사라지고 공식 MODU 로고가 남도록 구성하여, 기능 화면에서 브랜드 엔딩 카드로의 전환이 단절되지 않도록 한다.

도구 선택 측면에서는 이미지 생성과 영상 변환의 역할을 분리했다.  
먼저 Ideogram을 통해 가상 브랜드 MODU의 로고와 앱 UI 기준 이미지를 새로 생성한다. 특히 앱 UI 기준 이미지는 `2026 7월`, `오늘`, 주간 캘린더, `기상`, `아침 운동`, `회의`, `아침 식사` 일정 카드가 보이도록 구체화한다. 이후 이 기준 비주얼을 바탕으로 씬별 키비주얼을 제작하고, KLING을 활용해 필요한 장면만 짧은 영상으로 변환한다. 이 방식은 영상 생성 크레딧을 절약하면서도 광고에 필요한 움직임과 실제 앱 광고 같은 구체성을 확보할 수 있는 현실적인 전략이다.

또한 로고와 텍스트는 영상 생성 과정에서 왜곡될 가능성이 있으므로, 씬 4 생성 단계에서는 공식 로고 이미지를 최우선 고정 기준으로 사용하고, 한글 슬로건과 엔딩 카피는 CapCut에서 직접 배치한다.  
이는 광고의 마지막 3초 안에 브랜드명, 슬로건, 엔딩 카피를 명확하게 보여주기 위한 선택이다.

오디오 측면에서는 Suno로 생성한 경쾌한 전자음악 BGM을 사용하고, CapCut TTS로 발랄한 여성 내레이션을 제작한다.  
시각 요소와 청각 요소가 모두 AI 생성 소스에 기반하도록 구성하되, CapCut은 컷 편집, 자막, 로고 배치, 오디오 레벨 조정 등 통합 편집 용도로 제한해 사용한다.

최종 영상은 1080p를 목표로 제작하되, 생성 도구의 제한이 발생할 경우 과제 허용 기준에 따라 720p 이상으로 제작한다.  
이러한 방식은 제한된 제작 환경에서도 브랜드 톤앤매너, 메시지 전달력, 제작 가능성을 균형 있게 확보할 수 있는 AI 기반 광고 제작 전략이다.

---

## 16. 리스크 및 대응 방안

| 발생 가능 문제 | 원인 | 대응 전략 |
|---|---|---|
| 로고나 텍스트가 깨짐 | 이미지·영상 생성 AI가 글자를 정확히 유지하지 못함 | 최종 로고와 카피는 CapCut에서 오버레이로 배치 |
| 한글 UI가 깨지거나 임의 문자로 나옴 | 긴 한글 문장과 작은 글자를 이미지 생성 AI가 안정적으로 처리하지 못함 | `기상`, `회의`처럼 짧은 라벨만 사용하고, 네거티브 프롬프트에 garbled Korean, fake words 등을 명시 |
| MODU 워드마크가 틀림 | AI가 브랜드명을 임의로 변형함 | “Keep the MODU wordmark exactly in English”를 반복하고, 오탈자 결과는 폐기 |
| 로고·UI 기준 이미지를 첨부해도 다른 디자인이 생성됨 | 생성 AI가 참고 이미지를 스타일 참고로만 해석함 | 로고 이미지를 최우선 고정 기준으로 명시하고, 씬 3에서는 앱 UI 기준 이미지를 고정 템플릿으로 지정하며 `Do not redesign` 문장을 반복 |
| 씬별 스타일이 달라짐 | 각 프롬프트의 스타일 키워드가 다름 | 네온 블루, 네온 핑크, 다크 네이비, 딥 퍼플 등 공통 키워드 반복 |
| 씬 3에서 씬 4로 넘어갈 때 배경과 중앙축이 달라 보임 | 엔딩 이미지를 독립적인 새 배경으로 생성함 | 씬 3 마지막 프레임을 씬 4의 고정 연속성 레퍼런스로 첨부하고 회로 패턴·좌우 조명·그리드 바닥·중앙 위치를 유지 |
| 씬 4 영상 변환 중 로고 글자가 흔들리거나 재생성됨 | 입자가 로고를 새로 형성하도록 과도하게 지시함 | 로고는 소스 이미지에서 처음부터 고정하고, 잔여 아우라 소멸과 전체 워드마크의 1회 글로우만 애니메이션으로 적용 |
| 영상 생성 크레딧 부족 | KLING 등 영상 도구의 무료 제한 | 씬 수를 4개로 제한하고, CapCut 모션으로 대체 |
| 화면 비율이 섞임 | 도구별 기본 출력 비율 차이 | 최종 편집에서 16:9로 통일 |
| 오디오 톤이 과함 | BGM이 내레이션보다 강함 | BGM 볼륨을 낮추고 내레이션 중심으로 믹싱 |
| 앱 UI가 실제 앱처럼 보이지 않음 | 프롬프트가 추상적임 | dashboard, task cards, calendar widgets, checklist icons 등 구체 키워드 사용 |
| 광고 메시지가 약함 | 컷은 화려하지만 문제-해결 구조가 약함 | 씬별 내레이션을 문제 → 전환 → 해결 → 브랜드 각인 순서로 배치 |

---

## 17. 제출 전 최종 검수 체크리스트

| 체크 항목 | 완료 여부 |
|---|---|
| 브랜드명, 타겟, 톤앤매너, USP가 문서에 포함되어 있는가? | □ |
| 광고 목적과 핵심 메시지가 한 문장으로 정리되어 있는가? | □ |
| 씬별 필수 필드가 모두 포함되어 있는가? | □ |
| 최소 1개 씬의 프롬프트 수정 전/후 기록이 있는가? | □ |
| 이미지 생성 AI, 비디오 생성/변환 AI, 오디오 생성 AI를 각각 1종 이상 사용했는가? | □ |
| 각 도구를 왜 선택했는지 설명되어 있는가? | □ |
| 최종 영상이 10초 이내인가? | □ |
| AI 생성 시각 요소와 AI 생성 청각 요소가 모두 포함되어 있는가? | □ |
| 마지막 3초 구간에 브랜드명, 로고, 슬로건, CTA 중 1개 이상이 들어가는가? | □ |
| 영상 파일명이 문서의 파일명 규칙과 일치하는가? | □ |
| 최종 MP4 해상도가 720p 이상인가? | □ |
| 스토리보드 문서를 PDF로 변환했는가? | □ |
| MODU 로고와 앱 UI 기준 이미지를 새로 생성했는가? | □ |
| 앱 UI 기준 이미지에 `2026 7월`, `오늘`, 주간 캘린더, 4개 일정 카드가 포함되어 있는가? | □ |
| `MODU` 워드마크와 한글 UI가 읽을 수 있는 수준으로 생성되었는가? | □ |
| 씬 2에서 최종 대시보드가 노출되지 않고 공식 MODU 로고와 흡수 효과만 보이는가? | □ |
| 씬 3에서 앱 UI 기준 이미지의 캘린더·일정 카드·하단 내비게이션 구조가 유지되었는가? | □ |
| 씬 4가 씬 3과 동일한 회로 보드 배경, 좌우 퍼플·블루 조명, 중앙축을 유지하는가? | □ |
| 씬 4의 MODU 로고가 공식 로고와 동일하며 영상 변환 중 글자 형태가 흔들리지 않는가? | □ |
| 씬 4의 한글 슬로건과 엔딩 카피를 생성 이미지가 아닌 CapCut 텍스트로 배치했는가? | □ |
| 씬 1·2·3 원본 영상을 각각 2초·2초·3초의 핵심 구간으로 트리밍했는가? | □ |
| 실제 생성 결과 요약과 파일명을 최종 파일 기준으로 업데이트했는가? | □ |

---

## 18. 제출 전 업데이트가 필요한 항목

현재 문서는 제작 계획과 스토리보드 중심으로 정리되어 있다.  
최종 제출 전에는 실제 생성 결과를 반영해 아래 항목을 반드시 업데이트한다.

| 업데이트 항목 | 입력할 내용 |
|---|---|
| 실제 사용한 이미지 생성 도구 | Ideogram으로 로고·앱 UI·씬 이미지를 실제 생성했는지, 다른 도구로 대체했는지 |
| 실제 사용한 영상 변환 도구 | KLING을 실제 사용했는지, 일부 장면을 CapCut 모션으로 대체했는지 |
| 실제 BGM 생성 결과 | Suno 결과 파일명 또는 링크 |
| 실제 내레이션 결과 | CapCut TTS 파일명 또는 편집 프로젝트 내 위치 |
| 각 씬 출력 결과 요약 | 생성된 이미지/영상이 의도와 얼마나 일치했는지 한 줄로 수정 |
| 앱 UI 실제 생성 결과 | `MODU` 오탈자 여부, 한글 UI 가독성, 토요일 9일 강조, 4개 일정 카드 포함 여부 기록 |
| 실제 결과 파일명 | 최종 저장 파일명과 문서의 파일명 규칙 일치 여부 |
| 최종 영상 스펙 | 길이, 해상도, 프레임레이트, 코덱 |
| 프롬프트 수정 전/후 | 실제 생성 과정에서 문제가 있었던 씬으로 수정하면 더 설득력 있음 |
| 씬 4 실제 생성 결과 | 공식 MODU 로고 유지 여부, 씬 3 배경 연속성, 잔여 폰 아우라·입자 강도, 카피 여백 확보 여부 기록 |
| 실제 장면별 사용 구간 | 씬 1·2·3 원본 영상에서 최종 타임라인에 사용한 인·아웃 시점 기록 |
---

## 19. 최종 내용 검토 결과

### 19-1. 스토리 흐름 검토

| 검토 항목 | 결과 |
|---|---|
| 씬 1의 역할 | 현실에서 할 일이 폭주하는 문제 상황 제시 |
| 씬 2의 역할 | 씬 1의 종이·포스트잇·홀로그램 정보가 MODU 스마트폰으로 흡수되는 전환 |
| 씬 3의 역할 | 수집된 정보가 고정된 MODU UI에서 일정 카드와 체크 요소로 활성화되는 해결 장면 |
| 씬 4의 역할 | 씬 3의 배경과 중앙축을 유지하며 스마트폰에서 공식 MODU 로고 엔딩 카드로 연결 |
| 전체 구조 | 문제 제시 → 정보 수집 → 자동 정리 → 브랜드 각인의 인과관계가 명확함 |

### 19-2. 브랜드 일관성 검토

- 공식 MODU 로고 이미지를 씬 2·3·4의 최우선 고정 기준으로 지정하였다.
- 씬 3과 씬 4는 동일한 다크 네이비·딥 퍼플 회로 보드 배경, 왼쪽 퍼플·오른쪽 블루 글로우, 그리드 바닥을 유지하도록 통일하였다.
- 씬 4에서는 미래도시 빌딩이나 새로운 배경을 생성하지 않도록 네거티브 프롬프트를 보강하였다.
- 한글 슬로건과 엔딩 카피는 이미지 생성 AI에 맡기지 않고 CapCut에서 직접 입력하도록 통일하였다.

### 19-3. 길이 및 편집 가능성 검토

- 최종 구성은 씬 1 2초, 씬 2 2초, 씬 3 3초, 씬 4 3초로 총 10초이다.
- 현재 확인된 생성 원본은 씬 1 약 3.04초, 씬 2 8.00초, 씬 3 약 4.01초이므로 모두 최종 타임라인에 맞는 핵심 구간 트리밍이 필요하다.
- 씬 2는 첫 흡수 사이클이 끝나고 입자가 스마트폰 중앙에 모인 상태에서 종료하도록 편집한다.
- 씬 3은 스마트폰과 앱 UI가 안정적으로 보이는 마지막 프레임을 확보해 씬 4의 중앙 로고 위치와 연결한다.
- 씬 3과 씬 4 사이에는 긴 디졸브보다 0.15~0.25초의 짧은 네온 플래시 또는 입자 디졸브가 적합하다.

### 19-4. 프롬프트 안정성 검토

- 씬 4 영상 프롬프트에서 로고를 입자로 새로 만들도록 지시하지 않고, 처음부터 고정된 로고 주변의 잔여 아우라와 입자만 움직이도록 수정하였다.
- 씬 3과 씬 4 모두 `Do not redesign`, `Do not rewrite`, `Do not regenerate` 조건을 포함해 로고·UI 변형 위험을 줄였다.
- 씬 4 이미지에는 스마트폰 전체나 앱 UI가 다시 나타나지 않도록 제한하고, 옅은 폰 형태의 잔광만 허용하였다.
- 장면별 역할이 중복되지 않도록 씬 2는 최종 UI 비노출, 씬 3은 기능 UI 공개, 씬 4는 로고와 카피 중심으로 구분하였다.

### 19-5. 최종 제출 전 남은 작업

1. 씬 4 이미지와 영상 생성 후 공식 로고 일치 여부를 확인한다.
2. 씬 1·2·3 영상의 최종 사용 구간을 CapCut에서 확정한다.
3. 씬 4에 `할 일 폭주? MODU 정리해.`와 `나의 하루를 한눈에.`를 직접 입력한다.
4. BGM, 내레이션, 효과음의 음량을 조정한 뒤 전체 길이가 10초 이내인지 확인한다.
5. 최종 MP4의 해상도, 프레임레이트, 코덱과 문서의 실제 결과 파일명을 업데이트한다.
