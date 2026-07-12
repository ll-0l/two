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

이번 제작에서는 **Ideogram, KLING, Suno, CapCut TTS, CapCut**을 활용한다.  
이미지, 영상, 오디오, 내레이션, 편집 도구의 역할을 분리하고, 각 도구가 가진 장점을 활용하여 다음과 같은 제작 흐름을 설계한다.

> 기획 의도 정의 → 로고·앱 UI 기준 이미지 신규 생성 → 씬별 프롬프트 설계 → Ideogram 이미지 생성 → KLING 영상 변환 → 오디오·내레이션 생성 → CapCut 통합 편집 → 최종 MP4 출력

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
| 전환 | 씬 1의 종이·메모·일정 조각이 UI가 없는 MODU 스마트폰 화면 안으로 흡수되기 시작 |
| 해결 | 흡수된 정보가 캘린더와 일정 카드로 조립되어 한 화면에 자동 정리 |
| 브랜드 각인 | MODU 로고, 슬로건, 엔딩 카피로 앱의 가치를 명확히 인식 |

---

## 4. 제작 파이프라인

본 광고는 AI 생성 결과물을 주된 소스로 사용하고, 편집 도구는 통합 편집 용도로만 사용한다.  
특히 영상 생성 도구는 크레딧 소모가 크기 때문에, 먼저 이미지 단계에서 구도와 스타일을 확정한 뒤 필요한 컷만 영상 변환을 시도한다.

| 단계 | 작업 내용 | 사용 도구 | 의사결정 이유 |
|---|---|---|---|
| 1단계 | 브랜드 콘셉트와 광고 메시지 정의 | ChatGPT, 수동 기획 | 영상 생성 전 메시지와 장면 구조를 고정하기 위해 사용 |
| 2단계 | MODU 로고와 앱 UI 기준 이미지 신규 생성 | Ideogram | 가상 브랜드이므로 기존 소스 없이 브랜드 기준 비주얼을 먼저 확정하기 위해 사용 |
| 3단계 | 씬별 키비주얼 생성 및 정지 이미지를 짧은 모션 영상으로 변환 | Ideogram, KLING | 확정한 로고·앱 UI의 톤을 기준으로 씬 이미지를 만들고, 필요한 컷만 영상화해 크레딧을 절약 |
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
| 이미지 생성 | Ideogram | MODU 로고, 앱 UI 기준 이미지, 씬별 키비주얼, 엔딩 이미지 신규 생성 | 가상 브랜드이므로 기존 로고나 앱 UI 소스가 없다. 따라서 Ideogram에서 브랜드 기준이 되는 로고와 앱 UI를 먼저 생성한 뒤, 그 톤을 기준으로 씬 이미지를 제작한다. | Google Whisk, ChatGPT 이미지 생성, Canva AI 이미지 생성 |
| 비디오 생성/변환 | KLING | Ideogram으로 생성한 정지 이미지를 짧은 모션 영상으로 변환 | 이미지 기반 영상 변환과 짧은 광고 컷 제작에 적합하고, 네온 글로우·카메라 무빙·디지털 전환감을 구현하기 위해 사용 | CapCut 모션, KLING, Pika |
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
| MODU 앱 UI 기준 이미지 | 씬 3의 최종 대시보드 고정 기준 및 씬 2의 스마트폰·브랜드 색상 참고 | `modu_app_ui_reference.png` | Ideogram에서 앱 대시보드 UI 프롬프트로 생성 |
| 씬 1 전환 레퍼런스 이미지 | 씬 2에서 동일한 종이·포스트잇·홀로그램 카드와 네온 공간을 유지하기 위한 기준 | `scene01_task_overload.png` | 실제 생성된 씬 1 결과 이미지를 주요 이미지 레퍼런스로 사용 |
| 브랜드 컬러 기준 | 전체 영상의 톤앤매너 통일 | 별도 파일 없음 | 다크 네이비, 딥 퍼플, 네온 블루, 네온 핑크를 모든 프롬프트에 반복 적용 |

로고와 앱 UI가 먼저 확정되어야 이후 씬 2, 씬 3, 씬 4의 스타일이 흔들리지 않는다.  
따라서 제작 순서는 **로고 생성 → 앱 UI 기준 이미지 생성 → 씬별 이미지 생성 → 영상 변환 → 편집** 순서로 진행한다.

#### MODU 로고 신규 생성 프롬프트

```text
clean futuristic wordmark logo for a virtual AI productivity planner app named MODU, modern sans-serif typography, sleek and minimal design, premium tech branding, subtle neon blue and neon pink glow accents, dark navy or deep purple background, the letter U subtly styled with a check mark or completion motif, digital and youthful mood, cyberpunk-inspired but clean and readable, centered composition, high contrast, professional logo presentation, no mockup hands, no extra objects, no long slogan
```

#### MODU 앱 UI 기준 이미지 신규 생성 프롬프트

아래 프롬프트는 MODU의 **앱 UI 기준 이미지**를 만들기 위한 최종 수정본이다.  
기존의 추상적인 “생산성 앱 대시보드” 표현에서 더 나아가, 실제 화면에 들어갈 날짜, 캘린더, 일정 카드, 한글 라벨, 하단 내비게이션까지 구체적으로 지정한다. 이 이미지는 씬 3의 최종 UI를 고정하는 주요 기준으로 사용하고, 씬 2에서는 스마트폰 형태와 브랜드 색상만 참고한다. 씬 2의 떠다니는 소품과 공간 분위기는 씬 1 결과 이미지를 주요 레퍼런스로 사용한다.

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
- 씬 1~3은 이미지 기반 모션을 적용하고, 씬 4는 로고·카피 중심의 정지 엔딩 카드로 구성한다.
- 동일한 네온 블루·네온 핑크·다크 네이비 배경 스타일을 반복 사용하여 브랜드 톤을 유지한다.
- KLING 사용이 어렵거나 크레딧이 부족할 경우 CapCut 모션을 대체 도구로 사용한다.
- 기존 MODU 로고와 앱 UI가 없으므로, 먼저 로고 1장과 앱 UI 1장을 신규 생성해 기준 비주얼로 확정한다.
- 앱 UI 기준 이미지는 `2026 7월`, `오늘`, 주간 캘린더, 4개 일정 카드가 보이는 화면으로 구체화해 실제 앱처럼 보이게 한다.
- 씬 2에서는 씬 1 결과 이미지의 종이·포스트잇·홀로그램 카드와 네온 조명을 유지하고, 확정한 MODU 로고와 스마트폰 형태만 적용한다.
- 씬 3~4에서는 확정한 로고와 앱 UI의 색상, 형태, 일정 카드 스타일, 네온 강조 방식을 반복 사용해 브랜드 일관성을 유지한다.
- Ideogram 크레딧이 부족할 경우 로고와 앱 UI를 먼저 만들고, 나머지 씬은 CapCut 모션·배경·자막 조합으로 범위를 줄인다.
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
| 씬 2 | 2초 | 흡수 전환 | 씬 1의 종이·메모·일정 조각이 최종 UI가 없는 MODU 스마트폰 안으로 빨려 들어감 | MODU가 모두 정리해. |
| 씬 3 | 3초 | 정리 완성 | 씬 2에서 모인 입자가 캘린더와 네 개의 일정 카드로 조립되어 최종 UI가 완성됨 | 일정, 과제, 약속까지 한눈에. |
| 씬 4 | 3초 | 브랜드 각인 | MODU 로고, 슬로건, 엔딩 카피 노출 | 나의 하루를 한눈에. |

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
| KLING 영상 변환 프롬프트 원문 | 2-second commercial opening shot using the original image composition.Preserve the same person, face, body position, laptop, desk, room layout, lighting, and all existing objects. The overwhelmed person remains seated in the center, holding both sides of their head, with only subtle natural breathing and slight movement in the hair and clothes.Dozens of existing papers, sticky notes, document sheets, calendar pages, checklists, alarm icons, clock symbols, deadline markers, and translucent holographic task cards begin lifting from the cluttered room and swirling chaotically around the person. The tasks rotate, flutter, overlap, and fly past the foreground at different speeds, creating strong depth, parallax, and a feeling of mental overload. Some papers move rapidly across the camera, while sticky notes circle above the person’s head. Small glowing checklist icons, calendar symbols, notification badges, and deadline alerts appear between the floating documents. The movement should feel crowded, urgent, overwhelming, and slightly out of control, as if unfinished tasks are filling the entire room. Use a subtle cinematic push-in toward the person, combined with very slight handheld camera shake. The laptop and desk remain stable while nearby loose papers tremble and lift into the air. Neon blue and neon pink reflections pulse gently across the papers and the person’s face, maintaining the futuristic cyberpunk atmosphere. Fast energetic movement, busy morning tension, realistic paper physics, cinematic motion blur, strong foreground and background separation, premium commercial quality, dark navy, neon blue and neon pink lighting. Do not change the person’s identity or facial features. Do not move or deform the hands. Do not distort the laptop, desk, cups, clocks, or room. No new person, no face morphing, no extra limbs, no duplicated hands, no readable generated text, no app interface, no smartphone UI, no central dashboard, no camera rotation, no extreme zoom, no scene transition. |
| 출력 결과 요약 | 네온 미래도시 감성이 입혀진 현실적인 일상 혼란 장면을 통해 MODU가 필요한 문제 상황을 제시하는 오프닝 키비주얼 확보 예정 |
| 생성 결과 파일명 또는 링크 | `scene01_task_overload.png` / `scene01_task_overload_motion.mp4` |

---

## 씬 2. MODU 실행 / 현실에서 앱으로 전환

### 기본 정보

| 항목 | 내용 |
|---|---|
| 씬 번호 | 2 |
| 씬 길이 | 2초 |
| 목표 메시지 | 씬 1의 혼란스러운 할 일 요소들이 MODU 스마트폰으로 흡수되며 정리가 시작된다는 전환을 보여준다. |
| 내레이션 또는 화면 카피 | **MODU가 모두 정리해.** |
| 사용 도구 및 목적 | 씬 1 결과 이미지를 **주요 시각 레퍼런스**로 사용해 동일한 종이·포스트잇·홀로그램 카드와 네온 색감을 유지한다. Ideogram에서 최종 UI가 없는 앱 실행 키비주얼을 만들고, KLING에서 일정 조각들이 화면 안으로 빨려 들어가는 모션을 적용한다. |
| 생성 결과 파일명 또는 링크 | `scene02_modu_launch.png` / `scene02_modu_launch_motion.mp4` |

### 화면 구성

씬 1 레퍼런스 이미지에 보이는 **큰 파란색·분홍색 종이, 노란 포스트잇, 청록색 반투명 홀로그램 카드, 체크리스트 조각과 알림 기호**를 동일한 색감과 형태로 유지한다. 중앙에는 스마트폰 전체가 정면으로 등장하며, 기존 인물과 복잡한 방은 바깥쪽에 희미하게 남아 있다가 디지털 공간으로 서서히 전환된다.

스마트폰 화면에는 씬 3의 최종 일정 UI를 미리 보여주지 않는다. 화면은 어둡고 광택이 있는 상태로 유지하며, 상단의 정확한 `MODU` 영문 워드마크와 중앙의 네온 흡수 지점만 표시한다. 주변에 떠 있는 일정 조각은 이동 방향을 바꾸어 스마트폰 화면 안으로 빨려 들어가고, 청록색과 분홍색의 작은 디지털 입자로 변환된다.

### 이미지 생성 프롬프트 원문

**주요 레퍼런스: 씬 1 결과 이미지**

```text
Use the supplied scene 1 reference image as the primary visual reference and preserve its overall visual identity.

Maintain the same chaotic everyday workspace atmosphere, dark compact room, centered composition, deep navy shadows, neon blue lighting, neon pink lighting, cinematic contrast, and cyberpunk-inspired mood from the reference image.

Preserve the same types of floating elements visible in the reference image: large blue paper sheets, pink paper sheets, yellow sticky notes, translucent cyan holographic cards, glowing checklist panels, calendar-like fragments, notification symbols, and scattered paper documents. Match their colors, glow, layered depth, motion-blur appearance, and chaotic visual density.

Transform the scene into the beginning of the MODU app launch transition. A complete smartphone appears upright in the center of the frame, full front view, entire phone visible from top to bottom, straight-on angle, centered composition.

The smartphone emerges behind the same floating papers and holographic cards from the scene 1 reference image. A large blue sheet remains close to the foreground, partially crossing the frame, while pink papers, yellow sticky notes, and cyan holographic cards surround the smartphone at different depths.

The smartphone screen must remain mostly dark and glossy. Do not show the final MODU dashboard or any completed app interface. Show only the MODU wordmark exactly in English near the top of the screen, glowing in neon blue and neon pink. In the center of the dark screen, show a subtle circular digital energy field, soft vortex light, or glowing data intake point.

The floating papers, sticky notes, checklist fragments, calendar pieces, notification symbols, and holographic task cards begin curving toward the smartphone screen, suggesting that everyday chaos is being absorbed and organized by MODU.

Gradually reduce the visibility of the existing person and cluttered room behind the smartphone, blending them into a dark futuristic digital environment. Keep faint traces of the original room near the outer edges while the central area transforms into a clean circuit-board space with purple glow on the left, blue glow on the right, and subtle digital grid reflections.

The image should represent the transition point between scene 1 and scene 2: the chaotic task elements from the reference image are still visible, but the smartphone has appeared as the solution.

Premium AI productivity app commercial style, cinematic depth, strong foreground parallax, high contrast, clean central focus, youthful futuristic mood.

Negative prompt: completed app dashboard, calendar UI, schedule cards, Korean dashboard text, bottom navigation bar, different app design, random English interface text, unrelated icons, futuristic city skyline, new person, additional people, hands, fingers, face close-up, cropped phone, tilted phone, side view, missing phone edges, misspelled MODU, distorted MODU logo, duplicate logo, unreadable text, garbled Korean, random letters, warped screen, blurry phone, low resolution, watermark, signature
```

### KLING 영상 변환 프롬프트 원문

```text
2-second commercial transition shot based on the supplied scene 1 reference image and the generated scene 2 key visual.

Preserve the visual identity of scene 1: the same dark cluttered workspace mood, neon blue and neon pink lighting, large blue and pink paper sheets, yellow sticky notes, translucent cyan holographic cards, checklist fragments, calendar pieces, and glowing notification symbols.

Keep the complete smartphone centered, upright, fully visible, and straight-on. The phone screen remains dark and glossy, showing only the MODU wordmark exactly in English at the top and a subtle circular neon energy intake point in the center. Do not reveal the final app dashboard.

At the beginning, the floating task elements continue moving chaotically around the smartphone. A large blue foreground sheet sweeps across the camera while pink papers and yellow sticky notes flutter at different depths. The cyan holographic cards rotate gently and maintain the same glowing appearance as the scene 1 reference.

The scattered papers, sticky notes, checklist fragments, calendar pieces, holographic cards, and notification particles gradually change direction and curve toward the smartphone screen. Their chaotic trajectories become smooth spiral streams, as if the phone is magnetically collecting every unfinished task.

As each element reaches the screen, it transforms into tiny neon cyan and pink digital particles and is absorbed into the central glowing point. Preserve realistic paper flutter, layered foreground parallax, cinematic motion blur, and smooth directional movement.

The existing person and cluttered room fade gradually into the dark background instead of disappearing abruptly. By the final moment, most task elements have entered the phone and a concentrated cluster of cyan and pink particles remains inside the dark screen, ready to form the dashboard in scene 3.

No completed dashboard, no calendar UI, no schedule cards, no bottom navigation bar, no readable Korean app content, no different app design, no random interface text, no sudden disappearance, no abrupt cut, no camera rotation, no extreme zoom, no distorted smartphone, no warped screen, no misspelled MODU, no garbled text.
```

### 출력 결과 요약

씬 1 레퍼런스 이미지의 종이, 포스트잇, 홀로그램 카드와 네온 조명을 유지한 상태에서 중앙에 MODU 스마트폰이 해결 도구로 등장한다. 최종 앱 UI는 노출하지 않고, 흩어진 일정 요소가 스마트폰 중앙으로 빨려 들어가 네온 디지털 입자로 변환되는 과정을 보여준다. 마지막에는 입자들이 화면 안에 모인 상태로 끝나 씬 3의 일정 UI 생성 장면으로 연결한다.

---

## 씬 3. 일정 자동 정리 / MODU 앱 UI 핵심 장면

### 기본 정보

| 항목 | 내용 |
|---|---|
| 씬 번호 | 3 |
| 씬 길이 | 3초 |
| 목표 메시지 | 씬 2에서 수집된 일정 정보가 MODU의 카드형 UI로 정돈되어 한 화면에 완성되는 기능적 가치를 전달한다. |
| 내레이션 또는 화면 카피 | **일정, 과제, 약속까지 한눈에.** |
| 사용 도구 및 목적 | MODU 앱 UI 기준 이미지를 **고정된 최종 디자인 템플릿**으로 사용한다. KLING에서는 씬 2 마지막의 네온 입자가 캘린더와 일정 카드로 조립되는 연출을 적용하되, 한글 UI와 MODU 워드마크는 다시 생성하거나 변형하지 않고 기준 이미지 그대로 유지한다. |
| 생성 결과 파일명 또는 링크 | `scene03_organized_dashboard.png` / `scene03_organized_dashboard_motion.mp4` |

### 화면 구성

씬 2와 동일한 정면 중앙 스마트폰 구도를 유지한다. 스마트폰 화면 상단에는 `MODU` 영문 워드마크가 표시되고, 화면 안에는 `2026 7월`, 큰 제목 `오늘`, 주간 캘린더 `월 화 수 목 금 토 일`, 날짜 4~10이 배치된다. 토요일 9일은 네온 시안으로 강조한다.

아래에는 `기상 7:00`, `아침 운동 8:00`, `회의 9:00`, `아침 식사 10:00` 네 개의 일정 카드를 세로로 정렬하고, `회의` 카드는 네온 블루·핑크 글로우와 작은 원형 프로필 아바타로 강조한다. 씬 2에서 모인 청록색·분홍색 입자는 일정 카드의 테두리와 체크리스트 기호로 정착하며, 최종적으로 모든 일정이 한 화면에 정돈된 상태를 보여준다.

### 이미지 생성 프롬프트 원문

**주요 레퍼런스: 확정된 MODU 앱 UI 기준 이미지**  
**연결 레퍼런스: 씬 2 결과 이미지**

```text
Use the confirmed MODU app UI reference image as the primary fixed design template. Preserve the same smartphone, exact straight-on full front view, centered composition, complete phone visibility, dark navy and deep purple interface, neon blue and neon pink highlights, circuit-board background, and subtle grid floor reflection.

Do not redesign or reinterpret the app interface. Keep the MODU wordmark exactly in English at the top header. Preserve the same Korean UI structure and visual hierarchy: “2026 7월”, large title “오늘”, the weekly calendar row “월 화 수 목 금 토 일” with dates 4 to 10, Saturday 9 highlighted in neon cyan, four vertically stacked schedule cards, and the bottom navigation bar with the glowing plus button in the center.

Keep the four schedule cards exactly as shown in the reference:
“기상” 7:00
“아침 운동” 8:00
“회의” 9:00
“아침 식사” 10:00

Preserve the stronger neon blue and pink glow around the “회의” card and the small circular profile avatars. Keep the Korean text clean, short, readable, and unchanged.

To connect with scene 2, include only subtle traces of neon cyan and pink digital particles settling into the card borders, checklist circles, calendar highlight, and interface lines, as if the previously absorbed task fragments have just finished assembling into this final organized dashboard. Do not cover or replace the interface.

Premium AI productivity app advertisement style, clean readable composition, high contrast, youthful digital mood, cyberpunk-inspired but minimal and professional.

Negative prompt: redesigned app UI, different app, different layout, random English placeholder text, changed Korean labels, missing calendar, missing schedule cards, missing bottom navigation, cropped phone, cropped screen, cut off edges, side view, tilted angle, hands, fingers, people, extra objects, messy UI, overcrowded design, tiny text, unreadable text, garbled Korean, broken Korean characters, fake words, misspelled MODU, distorted MODU logo, duplicate logo, blurry, low resolution, pixelated, warped screen, bad alignment, inconsistent icons, watermark, signature, artifacts
```

### KLING 영상 변환 프롬프트 원문

```text
3-second UI formation and reveal shot continuing from scene 2.

Keep the complete smartphone in exactly the same centered, upright, straight-on position. Begin with the concentrated cluster of neon cyan and pink digital particles already collected inside the dark screen from scene 2. Do not reset the composition and do not begin with unrelated objects.

Use the confirmed MODU dashboard reference as the fixed final interface. Do not redraw, replace, retype, or morph the MODU wordmark or Korean text. Reveal the existing final UI progressively while keeping every label and layout element stable and readable.

The collected particles spread through the screen and settle into the interface in a clear sequence. First, the header and “2026 7월” with “오늘” become visible. Next, the weekly calendar row appears with Saturday 9 highlighted in neon cyan. Then the four existing schedule cards are revealed one by one in order: “기상” 7:00, “아침 운동” 8:00, “회의” 9:00, and “아침 식사” 10:00.

The particles form the card borders, checklist circles, icons, and neon highlights rather than generating new text. The “회의” card receives the strongest neon blue and pink glow, and its existing circular profile avatars remain unchanged. After the full dashboard is visible, checklist circles softly activate in order and the bottom plus button gently pulses.

The final result should feel like all previously chaotic tasks have been collected and organized into one clean screen. Keep the futuristic circuit-board background softly glowing with purple on the left and blue on the right.

No text morphing, no retyping animation, no changed Korean labels, no warped text, no distorted MODU wordmark, no redesigned interface, no different app, no missing schedule cards, no extra objects, no camera rotation, no extreme zoom, no warped smartphone.
```

### 출력 결과 요약

씬 2에서 스마트폰 안으로 흡수된 청록색·분홍색 입자가 캘린더, 카드 테두리, 체크 기호와 글로우 효과로 정착한다. 이후 `2026 7월`, `오늘`, 주간 캘린더와 네 개의 일정 카드가 기준 이미지의 레이아웃을 유지한 채 순차적으로 드러나며, 흩어진 일정이 한 화면에 정돈되는 MODU의 핵심 기능을 전달한다.

---

## 씬 4. 브랜드 각인 / 엔딩 카드

| 항목 | 내용 |
|---|---|
| 씬 번호 | 4 |
| 씬 길이 | 3초 |
| 목표 메시지 | MODU의 브랜드명과 슬로건을 각인시키고 광고를 마무리한다. |
| 화면 구성 | 중앙에 새로 확정한 `MODU` 영문 워드마크가 크게 배치된다. 배경은 씬 3의 앱 UI와 연결되도록 다크 네이비·딥 퍼플, 네온 블루·핑크 글로우, 미래도시적 디지털 회로 보드 분위기를 유지한다. 한글 슬로건과 엔딩 카피는 이미지 생성 과정에서 깨질 수 있으므로 CapCut에서 직접 입력한다. |
| 내레이션 또는 화면 카피 | 나의 하루를 한눈에. |
| 사용 도구 및 목적 | Ideogram에서 MODU 워드마크 로고 엔딩 이미지를 새로 생성하고, KLING에서 로고 페이드인과 네온 글로우 펄스 모션을 적용한다. 최종 엔딩에서는 CapCut으로 슬로건과 엔딩 카피를 직접 배치해 가독성을 확보한다. |
| 이미지 생성 프롬프트 원문 | premium futuristic brand end card for a virtual AI productivity planner app named MODU, keep the MODU wordmark exactly in English at the center, clean modern sans-serif typography, sleek minimal wordmark logo, subtle neon blue and neon pink glow accents, dark navy and deep purple background, futuristic city-inspired digital circuit board background, purple glow on the left, blue glow on the right, subtle grid floor reflection, premium tech branding, cyberpunk-inspired but clean and readable, high contrast, centered composition, professional AI app brand advertisement style, leave clean empty space below the logo for Korean slogan overlay, 16:9 composition, no Korean text inside generated image, no mockup hands, no people, no extra objects. Negative prompt: misspelled MODU, distorted MODU logo, wrong brand name, duplicate logo, garbled text, Korean text, long slogan, watermark, signature, artifacts, blurry, low resolution, noisy image, amateur design, cluttered background |
| KLING 영상 변환 프롬프트 원문 | 3-second premium brand end card animation, MODU logo fades in at center, subtle neon blue and pink glow pulse, dark navy and deep purple futuristic digital background, soft city-light reflections, minimal movement, readable logo, no distortion, no extra objects, leave clean space below the logo for CapCut Korean slogan overlay |
| CapCut에서 직접 넣을 문구 | `MODU` / `할 일 폭주? MODU 정리해.` / `나의 하루를 한눈에.` |
| 출력 결과 요약 | MODU 로고와 한글 슬로건을 안정적으로 각인시킬 수 있는 브랜드 엔딩 화면 확보 예정 |
| 생성 결과 파일명 또는 링크 | `scene04_modu_endcard.png` / `scene04_modu_endcard_motion.mp4` |
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
- 씬 4에서는 BGM을 자연스럽게 마무리하고 로고 인지가 가능하도록 음량을 안정시킨다.

---

## 12. KLING 영상 변환 및 최종 편집 계획

영상 생성/변환은 **KLING**에서 진행하고, 최종 통합 편집은 **CapCut**에서 진행한다.  
KLING은 정지 이미지를 짧은 모션 영상으로 변환하는 용도로 사용하고, CapCut은 컷 편집, 자막, 로고 오버레이, 오디오 레벨 조정 등 통합 편집 용도로 사용한다.

### 편집 순서

1. 씬별 이미지 또는 영상 파일을 16:9 타임라인에 배치한다.
2. 각 씬 길이를 2초, 2초, 3초, 3초로 조정한다.
3. 씬 1에는 빠른 줌인 또는 흔들림 효과를 적용해 할 일 폭주 느낌을 준다.
4. 씬 2에는 씬 1과 동일한 종이·포스트잇·홀로그램 카드가 스마트폰 안으로 빨려 들어가는 흡수 모션과 네온 에너지 전환을 적용한다.
5. 씬 3에는 씬 2에서 모인 네온 입자가 캘린더와 일정 카드의 테두리로 정착하고, 최종 UI가 순차적으로 드러나는 모션을 적용한다.
6. 씬 4에는 로고 페이드인, 슬로건, 엔딩 카피를 순차적으로 배치한다.
7. Suno로 생성한 BGM과 CapCut TTS로 만든 내레이션을 삽입하고, 음량을 조정한다.
8. 최종 파일을 MP4 형식으로 출력한다.
9. 가능하면 1080p로 인코딩하고, 도구 제한이 있을 경우 720p 이상으로 출력한다.

---

## 13. 최종 영상 구성 타임라인

| 시간 | 화면 | 오디오/내레이션 | 편집 포인트 |
|---|---|---|---|
| 0:00~0:02 | 할 일 카드와 알림이 폭주하는 네온 화면 | 할 일이 너무 많아? | 빠른 줌인, 알림 효과음 |
| 0:02~0:04 | 씬 1의 종이·메모·홀로그램 카드가 UI 없는 MODU 스마트폰 화면 안으로 흡수됨 | MODU가 모두 정리해. | 종이 흡수 모션, 네온 입자 변환 |
| 0:04~0:07 | 씬 2에서 모인 입자가 `2026 7월`, `오늘`, 주간 캘린더와 4개 일정 카드로 조립되어 최종 MODU UI 완성 | 일정, 과제, 약속까지 한눈에. | UI 순차 공개, 회의 카드 글로우, 체크 사운드 |
| 0:07~0:10 | MODU 로고, 슬로건, 엔딩 카피 노출 | 나의 하루를 한눈에. | 로고 페이드인, 카피 순차 등장 |

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
브랜드의 핵심 메시지인 “흩어진 할 일을 MODU가 모두 정리해준다”를 시각적으로 보여주기 위해, 씬 1에서는 바쁜 일상 속 여러 준비물과 일정이 한꺼번에 몰린 현실적인 혼란 장면을 제시한다. 씬 2에서는 동일한 종이·포스트잇·홀로그램 카드가 최종 UI가 없는 MODU 스마트폰 안으로 흡수되고, 씬 3에서는 수집된 네온 입자가 캘린더와 일정 카드로 조립되어 최종 대시보드가 완성되는 흐름을 보여준다.

도구 선택 측면에서는 이미지 생성과 영상 변환의 역할을 분리했다.  
먼저 Ideogram을 통해 가상 브랜드 MODU의 로고와 앱 UI 기준 이미지를 새로 생성한다. 특히 앱 UI 기준 이미지는 `2026 7월`, `오늘`, 주간 캘린더, `기상`, `아침 운동`, `회의`, `아침 식사` 일정 카드가 보이도록 구체화한다. 이후 이 기준 비주얼을 바탕으로 씬별 키비주얼을 제작하고, KLING을 활용해 필요한 장면만 짧은 영상으로 변환한다. 이 방식은 영상 생성 크레딧을 절약하면서도 광고에 필요한 움직임과 실제 앱 광고 같은 구체성을 확보할 수 있는 현실적인 전략이다.

또한 로고와 텍스트는 영상 생성 과정에서 왜곡될 가능성이 있으므로, 최종 엔딩 구간에서는 CapCut을 활용해 로고 이미지와 카피를 안정적으로 배치한다.  
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
| 씬별 스타일이 달라짐 | 각 프롬프트의 스타일 키워드가 다름 | 네온 블루, 네온 핑크, 다크 네이비, 딥 퍼플 등 공통 키워드 반복 |
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

---
