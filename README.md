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

이번 제작에서는 **Ideogram, Runway, Suno, CapCut TTS, CapCut**을 활용한다.  
이미지, 영상, 오디오, 내레이션, 편집 도구의 역할을 분리하고, 각 도구가 가진 장점을 활용하여 다음과 같은 제작 흐름을 설계한다.

> 기획 의도 정의 → 씬별 프롬프트 설계 → 이미지 생성 → 영상 변환 → 오디오·내레이션 생성 → CapCut 통합 편집 → 최종 MP4 출력

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
| 2단계 | 씬별 키비주얼 생성 | Ideogram | 로고, UI, 짧은 카피 등 텍스트 포함 이미지 생성에 적합 |
| 3단계 | 정지 이미지를 짧은 모션 영상으로 변환 | Runway | 2~3초 광고 컷에 필요한 카메라 무빙과 디지털 전환감 구현 |
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
| 이미지 생성 | Ideogram | 키비주얼, 앱 UI, 로고 엔딩 이미지 생성 | 네온·사이버펑크 스타일 표현이 가능하고, 로고·카피·UI처럼 텍스트가 포함된 이미지 생성에 비교적 적합하기 때문에 사용 | 기존 MODU 로고/앱 UI 이미지 재활용, Google Whisk, ChatGPT 이미지 생성 |
| 비디오 생성/변환 | Runway | Ideogram으로 생성한 정지 이미지를 짧은 모션 영상으로 변환 | 이미지 기반 영상 변환 품질이 높고, 광고 컷처럼 카메라 무빙과 전환감을 줄 수 있기 때문에 사용 | CapCut 모션, Pika, Kling |
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

### 7-2. 크레딧 부족 및 도구 제한 대응 전략

영상 생성 도구는 크레딧 소모가 크고 무료 플랜에서는 대기열이나 해상도 제한이 발생할 수 있다. 따라서 다음 전략을 적용한다.

- 씬 수를 4개로 제한하여 재생성 횟수를 줄인다.
- 모든 씬을 영상 생성으로 만들기보다, 정지 이미지에 줌인·패닝·글리치 전환을 적용한다.
- 씬 1~3은 이미지 기반 모션을 적용하고, 씬 4는 로고·카피 중심의 정지 엔딩 카드로 구성한다.
- 동일한 네온 블루·네온 핑크·다크 네이비 배경 스타일을 반복 사용하여 브랜드 톤을 유지한다.
- Runway 사용이 어렵거나 크레딧이 부족할 경우 CapCut 모션을 대체 도구로 사용한다.
- Ideogram 크레딧이 부족할 경우 기존 MODU 로고와 앱 UI 이미지를 기준 소스로 재활용한다.
- 스타일 일관성이 필요한 경우 Google Whisk에 기존 MODU 로고/UI 이미지를 참조로 넣어 톤을 통일한다.
- 1080p 생성이 어려운 경우 과제 허용 기준에 따라 720p 이상으로 제작한다.

### 7-3. 스타일 일관성 유지 전략

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
- consistent with existing MODU logo and app UI style

추가로 다음 원칙을 적용한다.

- 로고는 한 번 확정한 이미지를 반복 사용해 브랜드 일관성을 유지한다.
- 앱 UI는 같은 색상, 같은 카드형 레이아웃, 같은 배경 톤을 유지한다.
- 영상 변환 단계에서는 과도한 카메라 회전이나 인물 움직임을 피하고, 줌·패닝·글로우·글리치처럼 안정적인 모션을 중심으로 적용한다.
- 화면 안 텍스트가 깨질 경우, 해당 텍스트는 영상 생성 결과물 안에 넣지 않고 CapCut 자막으로 다시 배치한다.

---

## 8. 씬 구성 요약

| 씬 번호 | 길이 | 역할 | 핵심 내용 | 카피/내레이션 |
|---|---:|---|---|---|
| 씬 1 | 2초 | 문제 제시 | 할 일 카드, 알림, 일정이 폭주하는 혼란스러운 화면 | 할 일이 너무 많아? |
| 씬 2 | 2초 | 전환 | MODU 앱이 실행되며 흩어진 정보가 모이기 시작 | MODU가 모두 정리해. |
| 씬 3 | 3초 | 해결 | 일정, 과제, 약속이 깔끔한 카드형 UI로 자동 정리 | 일정, 과제, 약속까지 한눈에. |
| 씬 4 | 3초 | 브랜드 각인 | MODU 로고, 슬로건, 엔딩 카피 노출 | 나의 하루를 한눈에. |

총 길이: **10초**

---

## 9. 씬별 스토리보드

## 씬 1. 할 일 폭주

| 항목 | 내용 |
|---|---|
| 씬 번호 | 1 |
| 씬 길이 | 2초 |
| 목표 메시지 | 사용자가 할 일과 일정에 압도되는 문제 상황을 보여준다. |
| 화면 구성 | 어두운 네이비·퍼플 배경 위에 할 일 카드, 알림창, 캘린더 조각, 메시지 팝업이 네온 블루와 핑크 컬러로 빠르게 떠오른다. 화면은 약간 혼란스럽지만 앱 광고처럼 깔끔하고 읽기 쉬운 느낌을 유지한다. |
| 내레이션 또는 화면 카피 | 할 일이 너무 많아? |
| 사용 도구 및 목적 | Ideogram으로 혼란스러운 디지털 할 일 폭주 장면을 만들고, Runway에서 짧은 줌인·흔들림 모션을 적용한다. Runway 사용이 어려운 경우 CapCut 모션으로 대체한다. |
| 이미지 생성 프롬프트 원문 | chaotic digital task overload scene for a futuristic AI productivity planner app advertisement, many floating task cards, calendar reminders, notification popups, checklist icons, dark navy and deep purple background, neon blue and neon pink highlights, cyberpunk-inspired but clean and readable, youthful digital mood, premium tech branding, high contrast, 16:9 composition, no real brand logos, no human face |
| 비디오 변환 프롬프트 원문 | 2-second commercial shot, slow push-in camera movement, floating task cards and notification popups gently moving toward the viewer, subtle digital shake, neon flicker, clean futuristic UI motion, keep all shapes readable, no distorted text, no face, no extra objects |
| 출력 결과 요약 | 네온 컬러의 할 일 카드와 알림이 화면에 쏟아지는 문제 제시용 키비주얼 확보 예정 |
| 생성 결과 파일명 또는 링크 | `scene01_task_overload.png` / `scene01_task_overload_motion.mp4` |

---

## 씬 2. MODU 실행

| 항목 | 내용 |
|---|---|
| 씬 번호 | 2 |
| 씬 길이 | 2초 |
| 목표 메시지 | MODU 앱이 혼란을 정리하는 해결 도구로 등장한다. |
| 화면 구성 | 스마트폰 화면 중앙에 MODU 앱 아이콘 또는 로고가 나타나고, 주변의 흩어진 할 일 카드들이 앱 화면 안으로 모이는 장면이다. 배경은 다크 네이비와 딥 퍼플을 유지하고, 로고 주변에 네온 블루·핑크 글로우를 적용한다. |
| 내레이션 또는 화면 카피 | MODU가 모두 정리해. |
| 사용 도구 및 목적 | 로고와 앱 실행 장면을 Ideogram에서 생성한다. 기존 MODU 로고와 앱 UI 색감을 기준으로 스타일을 맞추고, 생성된 이미지에 Runway에서 카드가 중앙으로 모이는 모션을 적용한다. |
| 이미지 생성 프롬프트 원문 | full front view of a modern smartphone displaying a futuristic AI productivity planner app named MODU, app logo visible on the screen, floating task cards and reminders moving toward the phone, dark navy and deep purple background, neon blue and neon pink glow accents, clean premium app advertisement style, cyberpunk-inspired but minimal and readable, centered composition, 16:9, high contrast, consistent with existing MODU logo and app UI style, no extra objects |
| 비디오 변환 프롬프트 원문 | 2-second commercial transition shot, floating task cards smoothly move into the smartphone screen, MODU logo remains stable and readable, neon blue and pink glow pulse, clean digital transformation, centered phone, no camera rotation, no text distortion |
| 출력 결과 요약 | MODU 앱이 실행되며 흩어진 정보가 모이는 전환 장면 확보 예정 |
| 생성 결과 파일명 또는 링크 | `scene02_modu_launch.png` / `scene02_modu_launch_motion.mp4` |

---

## 씬 3. 일정 자동 정리

| 항목 | 내용 |
|---|---|
| 씬 번호 | 3 |
| 씬 길이 | 3초 |
| 목표 메시지 | MODU가 일정과 할 일을 자동으로 분류해 한눈에 보여준다는 기능적 가치를 전달한다. |
| 화면 구성 | 스마트폰 앱 화면 안에 Today, Study, Work, Personal 같은 카드형 일정 목록이 깔끔하게 정렬되어 있다. 체크리스트, 캘린더, 우선순위 태그가 보이며 전체적으로 생산성 앱 대시보드처럼 보인다. |
| 내레이션 또는 화면 카피 | 일정, 과제, 약속까지 한눈에. |
| 사용 도구 및 목적 | 앞서 생성한 앱 실행 이미지를 기준으로 앱 대시보드 UI를 Ideogram에서 생성한다. 동일한 스타일 키워드를 사용해 씬 간 톤을 일관되게 유지하며, 생성된 정지 이미지에 Runway 또는 CapCut 모션으로 카드가 정렬되는 듯한 움직임을 적용한다. |
| 이미지 생성 프롬프트 원문 | clean futuristic smartphone app UI for an AI productivity planner named MODU, organized dashboard layout, task cards automatically sorted into Today, Study, Work, Personal, calendar widgets, checklist icons, priority tags, dark navy and purple background, neon blue and pink highlights, minimal premium interface, readable UI, balanced spacing, 16:9 app advertisement composition, high contrast, consistent with existing MODU logo and app UI style |
| 비디오 변환 프롬프트 원문 | 3-second smooth UI animation, task cards snap into an organized dashboard, gentle zoom-out, checklist icons glow when completed, clean futuristic productivity app motion, keep UI layout readable, no warped text, no extra objects |
| 출력 결과 요약 | 흩어진 할 일이 카드형 대시보드로 정리된 해결 장면 확보 예정 |
| 생성 결과 파일명 또는 링크 | `scene03_organized_dashboard.png` / `scene03_organized_dashboard_motion.mp4` |

---

## 씬 4. 브랜드 각인

| 항목 | 내용 |
|---|---|
| 씬 번호 | 4 |
| 씬 길이 | 3초 |
| 목표 메시지 | MODU의 브랜드명과 슬로건을 각인시키고 광고를 마무리한다. |
| 화면 구성 | 중앙에 확정된 MODU 로고 또는 워드마크가 크게 배치되고, 아래에 슬로건 “할 일 폭주? MODU 정리해.”와 엔딩 카피 “나의 하루를 한눈에.”가 순차적으로 등장한다. 배경은 다크 네이비 또는 딥 퍼플이며, 네온 블루와 핑크 글로우를 사용한다. |
| 내레이션 또는 화면 카피 | 나의 하루를 한눈에. |
| 사용 도구 및 목적 | 기존 MODU 로고 이미지를 기준 소스로 사용한다. 필요 시 Ideogram으로 브랜드 엔딩 배경을 만들고, CapCut에서 로고 페이드인, 슬로건, 엔딩 카피를 직접 배치해 텍스트 가독성을 확보한다. |
| 이미지 생성 프롬프트 원문 | clean futuristic wordmark logo end card for an AI productivity planner app named MODU, modern sans-serif typography, sleek and minimal design, premium tech branding, subtle neon blue and neon pink glow accents, dark navy and deep purple background, the letter U subtly styled with a check mark or completion motif, digital and youthful mood, cyberpunk-inspired but clean and readable, centered composition, high contrast, 16:9, professional logo presentation, consistent with existing MODU logo and app UI style, no mockup hands, no extra objects |
| 비디오 변환 프롬프트 원문 | 3-second premium brand end card animation, MODU logo fades in at center, subtle neon glow pulse, clean dark navy and purple background, minimal movement, readable logo, no distortion, no extra objects |
| 출력 결과 요약 | MODU 로고와 엔딩 카피가 강조된 브랜드 각인용 엔딩 화면 확보 예정 |
| 생성 결과 파일명 또는 링크 | `scene04_modu_endcard.png` / `scene04_modu_endcard_motion.mp4` |

---

## 10. 프롬프트 수정 전/후 기록

## 씬 2 프롬프트 개선 로그

| 항목 | 내용 |
|---|---|
| 대상 씬 | 씬 2. MODU 실행 |
| 수정 전 의도 | 스마트폰 화면에 MODU 앱 UI와 로고를 함께 보여주고 싶었다. |
| 수정 전 프롬프트 | futuristic smartphone app UI for productivity planner MODU, neon cyberpunk style, task cards, app logo, dark background |
| 발생한 문제 | 프롬프트가 짧아 로고와 UI의 스타일이 일관되지 않고, 화면 안에 불필요한 오브젝트가 섞일 가능성이 있었다. 또한 16:9 광고 화면인지, 스마트폰 정면 구도인지가 명확하지 않았다. |
| 수정 방향 | 스마트폰을 정면 구도로 고정하고, 다크 네이비·딥 퍼플 배경, 네온 블루·핑크 강조색, 프리미엄 앱 광고 스타일을 구체적으로 명시했다. 기존 MODU 로고와 앱 UI가 있으므로 “consistent with existing MODU logo and app UI style”을 추가해 브랜드 일관성을 강화했다. |
| 수정 후 프롬프트 | full front view of a modern smartphone displaying a futuristic AI productivity planner app named MODU, app logo visible on the screen, floating task cards and reminders moving toward the phone, dark navy and deep purple background, neon blue and neon pink glow accents, clean premium app advertisement style, cyberpunk-inspired but minimal and readable, centered composition, 16:9, high contrast, consistent with existing MODU logo and app UI style, no extra objects |
| 결과 변화 | 앱 실행 장면의 구도가 명확해졌고, MODU 로고와 앱 UI가 같은 브랜드 톤으로 보이도록 개선되었다. |

### 추가 개선 판단

텍스트가 들어가는 광고 컷은 AI 영상 변환 과정에서 글자가 깨지거나 로고 형태가 흔들릴 수 있다.  
따라서 씬 4의 로고와 카피는 영상 생성 결과물에만 의존하지 않고, 최종 편집 단계에서 CapCut 자막과 이미지 오버레이로 다시 배치한다.  
이 방식은 과제의 편집 도구 사용 범위인 컷 편집, 자막, 간단한 색보정, 오디오 레벨 조정 안에 포함되며, 광고 메시지의 가독성을 높이는 현실적인 제작 전략이다.

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
- 씬 1에서는 알림음과 글리치 효과음을 짧게 사용해 혼란감을 만든다.
- 씬 2에서는 전환음 또는 네온 플래시 효과음을 넣어 앱 실행감을 강조한다.
- 씬 3에서는 체크 완료 효과음을 넣어 “정리됨”의 감각을 전달한다.
- 씬 4에서는 BGM을 자연스럽게 마무리하고 로고 인지가 가능하도록 음량을 안정시킨다.

---

## 12. 최종 편집 계획

최종 편집은 **CapCut**에서 진행한다.  
편집 도구는 핵심 비주얼이나 오디오를 새로 만드는 용도가 아니라, AI로 생성한 이미지·영상·오디오 결과물을 하나의 광고로 연결하는 통합 편집 용도로 사용한다.

### 편집 순서

1. 씬별 이미지 또는 영상 파일을 16:9 타임라인에 배치한다.
2. 각 씬 길이를 2초, 2초, 3초, 3초로 조정한다.
3. 씬 1에는 빠른 줌인 또는 흔들림 효과를 적용해 할 일 폭주 느낌을 준다.
4. 씬 2에는 글리치 전환 또는 네온 플래시 효과를 적용해 MODU 실행감을 준다.
5. 씬 3에는 카드가 정리되는 듯한 패닝 또는 줌아웃 효과를 적용한다.
6. 씬 4에는 로고 페이드인, 슬로건, 엔딩 카피를 순차적으로 배치한다.
7. Suno로 생성한 BGM과 CapCut TTS로 만든 내레이션을 삽입하고, 음량을 조정한다.
8. 최종 파일을 MP4 형식으로 출력한다.
9. 가능하면 1080p로 인코딩하고, 도구 제한이 있을 경우 720p 이상으로 출력한다.

---

## 13. 최종 영상 구성 타임라인

| 시간 | 화면 | 오디오/내레이션 | 편집 포인트 |
|---|---|---|---|
| 0:00~0:02 | 할 일 카드와 알림이 폭주하는 네온 화면 | 할 일이 너무 많아? | 빠른 줌인, 알림 효과음 |
| 0:02~0:04 | MODU 앱 실행, 흩어진 카드가 중앙으로 모임 | MODU가 모두 정리해. | 글리치 전환, 네온 플래시 |
| 0:04~0:07 | 일정과 할 일이 카드형 UI로 자동 정리됨 | 일정, 과제, 약속까지 한눈에. | 카드 정렬 모션, 체크 사운드 |
| 0:07~0:10 | MODU 로고, 슬로건, 엔딩 카피 노출 | 나의 하루를 한눈에. | 로고 페이드인, 카피 순차 등장 |

---

## 14. 최종 결과 파일명 규칙

| 파일 종류 | 파일명 |
|---|---|
| 스토리보드 MD 문서 | `MODU_storyboard_shinuiryeong.md` |
| 스토리보드 PDF 문서 | `MODU_storyboard_shinuiryeong.pdf` |
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
브랜드의 핵심 메시지인 “흩어진 할 일을 MODU가 모두 정리해준다”를 시각적으로 보여주기 위해, 씬 1에서는 혼란스러운 알림과 일정 카드를 배치하고, 씬 3에서는 카드형 대시보드로 정리된 화면을 제시한다.

도구 선택 측면에서는 이미지 생성과 영상 변환의 역할을 분리했다.  
먼저 Ideogram을 통해 로고, 앱 UI, 키비주얼처럼 브랜드 인지가 중요한 정지 이미지를 생성한다. 이후 Runway를 활용해 필요한 장면만 짧은 영상으로 변환한다. 이 방식은 영상 생성 크레딧을 절약하면서도 광고에 필요한 움직임을 확보할 수 있는 현실적인 전략이다.

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
| 씬별 스타일이 달라짐 | 각 프롬프트의 스타일 키워드가 다름 | 네온 블루, 네온 핑크, 다크 네이비, 딥 퍼플 등 공통 키워드 반복 |
| 영상 생성 크레딧 부족 | Runway 등 영상 도구의 무료 제한 | 씬 수를 4개로 제한하고, CapCut 모션으로 대체 |
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
| 실제 생성 결과 요약과 파일명을 최종 파일 기준으로 업데이트했는가? | □ |

---

## 18. 제출 전 업데이트가 필요한 항목

현재 문서는 제작 계획과 스토리보드 중심으로 정리되어 있다.  
최종 제출 전에는 실제 생성 결과를 반영해 아래 항목을 반드시 업데이트한다.

| 업데이트 항목 | 입력할 내용 |
|---|---|
| 실제 사용한 이미지 생성 도구 | Ideogram을 실제 사용했는지, 다른 도구로 대체했는지 |
| 실제 사용한 영상 변환 도구 | Runway를 실제 사용했는지, CapCut 모션으로 대체했는지 |
| 실제 BGM 생성 결과 | Suno 결과 파일명 또는 링크 |
| 실제 내레이션 결과 | CapCut TTS 파일명 또는 편집 프로젝트 내 위치 |
| 각 씬 출력 결과 요약 | 생성된 이미지/영상이 의도와 얼마나 일치했는지 한 줄로 수정 |
| 실제 결과 파일명 | 최종 저장 파일명과 문서의 파일명 규칙 일치 여부 |
| 최종 영상 스펙 | 길이, 해상도, 프레임레이트, 코덱 |
| 프롬프트 수정 전/후 | 실제 생성 과정에서 문제가 있었던 씬으로 수정하면 더 설득력 있음 |

---
