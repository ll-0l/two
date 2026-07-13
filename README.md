<div class="cover">

# MODU AI 브랜드 광고 스토리보드

## 멀티모달 콘텐츠 제작 최종본

**제출자:** 신의령  
**브랜드:** MODU - 가상의 AI 일정·할 일 정리 플래너 앱  
**최종 영상:** 10초 / 16:9 / 1280x720 / 30fps

</div>

---

## 1. 제출 산출물

| 구분 | 제출 파일명 | 설명 |
|---|---|---|
| 스토리보드 PDF | `MODU_storyboard_shinuiryeong.pdf` | 브랜드 기획, 씬 구성, 프롬프트, 제작 의사결정 기록 |
| 최종 광고 영상 | `MODU_brand_ad_shinuiryeong_final_10s.mp4` | 생성형 AI 시각·청각 소스를 통합한 10초 광고 |
| 작업 증빙용 원본 | `MODU_storyboard_final_shinuiryeong.md` | PDF 제작에 사용한 Markdown 원본 |

MODU는 과제 수행을 위해 기획한 **가상 브랜드**이며 실제 출시 서비스가 아니다. 최종 광고는 **문제 제시 - MODU 실행 - 일정 정리 - 브랜드 각인**의 흐름으로 구성하였다.

---

## 2. 브랜드 아이덴티티와 캠페인 정의

| 항목 | 내용 |
|---|---|
| 브랜드명 | MODU |
| 발음 | 모두 |
| 브랜드 유형 | AI 일정·할 일 정리 플래너 앱 |
| 주요 타깃 | 할 일과 일정이 많은 20~30대 취업준비생, 프리랜서, 직장인 |
| 타깃의 문제 | 지원서, 과제, 회의, 약속, 개인 일정이 한꺼번에 쌓여 우선순위를 정하기 어렵다. |
| 톤앤매너 | 네온, 사이버펑크, 경쾌한 디지털 생산성 광고 |
| 시각 키워드 | 다크 네이비, 딥 퍼플, 네온 블루·핑크, 글로우, 카드형 UI |
| 브랜드 성격 | 빠르고 똑똑하지만 부담스럽지 않은 AI 비서 |
| USP | 흩어진 일정과 할 일을 AI가 자동으로 분류해 한 화면에 정리한다. |
| 캠페인 목적 | 브랜드 인지: 첫 노출에서 MODU를 '복잡한 하루를 정리하는 앱'으로 기억하게 한다. |
| 핵심 메시지 | **흩어진 일정, 과제, 약속을 MODU가 한눈에 정리해준다.** |
| 광고 구조 | 할 일 폭주 - 정보 흡수 - 정리된 대시보드 - 로고와 엔딩 카피 |

### 최종 화면 카피와 내레이션

| 구간 | 화면 카피 | 내레이션 |
|---|---|---|
| 문제 제시 | `할 일 폭주?` | `할 일이 너무 많아?` |
| 전환 | 없음 | `모두가 모~두 정리해줄게!` |
| 해결 | 없음 | `일정, 과제, 약속까지 한눈에.` |
| 엔딩 | `나의 하루를 한눈에.` | `모두.` |

TTS 입력에서는 브랜드 발음을 자연스럽게 강조하기 위해 `모오오두`처럼 길게 표기했으며, 문서에는 실제 청취 의미에 맞춰 `모~두`로 정리하였다. 화면에서는 영문 로고 `MODU`를 유지해 브랜드 표기를 통일하였다.

---

## 3. 제작 파이프라인과 도구 역할

> 기획 정의 - 로고·UI 기준 이미지 제작 - 씬별 키비주얼 생성 - 이미지 기반 영상 변환 - BGM·내레이션 생성 - CapCut 통합 편집 - 최종 MP4 검수

| 구분 | 실제 사용 도구 | 사용 목적과 강점 | 주의점 | 대체 도구 |
|---|---|---|---|---|
| 이미지 생성 | Ideogram, ChatGPT 이미지 생성 | 로고, 앱 UI 기준 이미지, 씬별 키비주얼 제작. 정지 화면에서 구도와 색을 먼저 확정해 영상 재생성 횟수를 줄였다. | 긴 한글 문구와 세부 UI는 변형될 수 있어 최종 자막은 편집 단계에서 추가했다. | Google Whisk, Canva AI 이미지 생성 |
| 비디오 생성·변환 | Google Flow | 종이·카드 흡수, 네온 입자, UI 활성화처럼 정지 이미지에 짧은 모션을 부여했다. | 로고와 UI가 변형되지 않도록 reference 고정과 금지 지시를 반복했다. | Kling, Pika |
| BGM 생성 | Suno | 10초 광고용 가사 없는 경쾌한 전자음악을 제작했다. | 내레이션과 충돌하지 않도록 보컬 없는 곡으로 제한했다. | Stable Audio, Beatoven |
| 음성 합성 | 클로바더빙 | 발랄한 여성 톤의 한국어 내레이션을 생성했다. | 영문 `MODU`를 글자 단위로 읽는 문제가 있어 음성 입력은 한글 `모두`로 변경했다. | 타입캐스트, TTSMaker, CapCut TTS |
| 통합 편집 | CapCut | 컷 편집, 화면 카피, 오디오 레벨 조정, 최종 인코딩에만 사용했다. | 핵심 비주얼과 오디오는 생성형 AI 결과물을 유지했다. | Canva Video, Premiere Pro |

### 도구 선택 비교 기록

초기에는 CapCut TTS를 사용하려 했으나 음성 생성 오류와 `MODU` 발음 문제가 발생했다. 클로바더빙으로 변경한 뒤 한국어 억양이 안정되고, 음성에서는 `모두`, 화면에서는 `MODU`를 사용하는 브랜드 언어 전략을 적용할 수 있었다. 영상 생성은 크레딧 소모를 줄이기 위해 로고·UI·씬별 구도를 이미지 단계에서 먼저 확정한 후 Google Flow로 짧게 변환하였다.

---

## 4. 일관성·크레딧·접근성 대응 전략

| 관리 항목 | 적용 방법 |
|---|---|
| 브랜드 일관성 | 공식 MODU 로고와 최종 앱 UI 이미지를 reference로 고정하고, 다크 네이비·딥 퍼플·네온 블루·핑크 팔레트를 모든 씬에 반복했다. |
| 화면 비율 | 모든 시각 소스를 16:9 기준으로 제작하고 CapCut 타임라인도 1280x720으로 통일했다. |
| 한글 가독성 | 생성 이미지 안의 긴 한글 문장을 최소화하고, 핵심 카피는 CapCut에서 직접 입력했다. |
| 영상 크레딧 절약 | 4씬으로 범위를 제한하고, 이미지 단계에서 구도와 스타일을 확정한 뒤 각 씬을 짧게 영상화했다. |
| 대기열·플랜 제한 | 이미지, 비디오, 오디오, TTS별 대체 도구를 사전에 기록했다. |
| 오디오 톤 통일 | 밝은 전자음악 BGM과 발랄한 여성 내레이션을 사용하고, BGM을 내레이션보다 낮게 믹싱했다. |
| 저작권·윤리 | 직접 촬영·유료 스톡을 사용하지 않고 생성형 AI 결과물을 주된 소스로 사용했다. 딥페이크·혐오·선정성·폭력 요소는 포함하지 않았다. |

---

## 5. 최종 영상 검수 결과

첨부된 최종 MP4를 기준으로 확인한 결과는 다음과 같다.

| 항목 | 실제 결과 | 과제 기준 | 판정 |
|---|---:|---:|---|
| 길이 | **10.000초** | 10초 이내 | 충족 |
| 해상도 | **1280x720** | 720p 이상 허용 | 충족 |
| 화면 비율 | **16:9** | 자유, 계획과 통일 | 충족 |
| 프레임레이트 | **30fps** | 권장 24~30fps | 충족 |
| 비디오 코덱 | **H.264** | 권장 H.264 | 충족 |
| 오디오 코덱 | **AAC / 48kHz / Stereo** | 권장 AAC | 충족 |
| AI 시각 요소 | 생성 이미지와 Google Flow 모션 | 필수 | 충족 |
| AI 청각 요소 | Suno BGM과 클로바더빙 내레이션 | 1개 이상 필수 | 충족 |
| 마지막 브랜드 장치 | 약 7.3초부터 MODU 로고, 마지막에 `나의 하루를 한눈에.` | 마지막 3~5초에 1개 이상 | 충족 |

최종본은 1080p 최대 권장 사양은 아니지만, 과제에서 허용한 **720p 이상** 조건을 충족한다. 무료 음성 도구 사용에 따른 `CLOVA Dubbing` 표기가 영상 우측 상단에 포함되어 있다.

---

## 6. 전체 타임라인

| 시간 | 씬 역할 | 화면 구성 | 화면 카피 | 내레이션 |
|---|---|---|---|---|
| 0:00~0:02.3 | 문제 제시 | 네온 조명의 복잡한 책상, 인물, 종이와 알림 카드가 폭주 | `할 일 폭주?` | `할 일이 너무 많아?` |
| 0:02.3~0:04.6 | 전환 | 종이·메모·디지털 카드가 MODU 스마트폰으로 흡수 | 없음 | `모두가 모~두 정리해줄게!` |
| 0:04.6~0:07.3 | 해결 | 정리된 MODU 앱 UI와 일정 카드가 활성화 | 없음 | `일정, 과제, 약속까지 한눈에.` |
| 0:07.3~0:10.0 | 브랜드 각인 | 스마트폰 실루엣에서 MODU 로고 엔딩 카드로 전환 | `나의 하루를 한눈에.` | `모두.` |

---

## 7. 씬별 스토리보드

## 씬 1. 할 일 폭주 - 현실의 혼란


| 필수 항목 | 내용 |
|---|---|
| 씬 번호 / 길이 | 씬 1 / 약 2.3초 |
| 목표 메시지 | 사용자가 과도한 할 일과 일정에 압도되는 문제를 즉시 보여준다. |
| 화면 구성 | 탑뷰에 가까운 네온 조명의 작업 공간. 인물이 머리를 감싸고 있고 노트북, 종이, 포스트잇, 디지털 카드가 주변을 빠르게 움직인다. |
| 내레이션 또는 카피 | 화면 `할 일 폭주?` / 내레이션 `할 일이 너무 많아?` |
| 사용 도구와 목적 | Ideogram·ChatGPT 이미지 생성: 키비주얼 제작 / Google Flow: 종이와 알림 카드의 폭주 모션 생성 / CapCut: 화면 카피 배치 |
| 출력 결과 요약 | 현실적인 과부하 상황과 네온 브랜드 톤이 한 장면에 결합되어 문제 제시가 명확해졌다. |
| 결과 파일명 | `scene01_overload_keyvisual.png` / `scene01_overload_motion.mp4` |

### 입력 프롬프트 - 이미지 생성

```text
chaotic everyday life scene for a 10-second commercial opening, showing a young adult overwhelmed by too many things to do, messy but visually appealing desk or compact room, laptop, planner, sticky notes, calendar page, coffee cup, study materials, resume papers, notebook, ringing smartphone, bag, clock, delivery box, to-do memo, multiple daily responsibilities all appearing at once, busy morning atmosphere, stressful and overwhelming mood, realistic daily life chaos, cinematic advertising composition, futuristic city-inspired mood, dark navy and deep purple environment, neon blue and neon pink lighting accents, subtle cyberpunk atmosphere, soft neon reflections, digital glow, premium tech brand aesthetic, high contrast, stylish and emotional commercial look, 16:9 composition, no app UI, no smartphone dashboard, no central interface, no clear human face, no brand logos, no readable long text.
```

### 입력 프롬프트 - 영상 변환

```text
2-second commercial opening shot using the original image composition. Preserve the overwhelmed person, laptop, desk, room layout, lighting, and existing objects. Papers, sticky notes, calendar pages, checklist icons, and translucent holographic task cards lift from the cluttered room and swirl chaotically around the person. Use subtle cinematic push-in, slight handheld shake, neon blue and neon pink reflections, realistic paper flutter, and motion blur. Do not reveal an app UI or smartphone dashboard.
```

---

## 씬 2. MODU 실행 - 정보를 한곳으로 흡수


| 필수 항목 | 내용 |
|---|---|
| 씬 번호 / 길이 | 씬 2 / 약 2.3초 |
| 목표 메시지 | MODU가 흩어진 할 일과 일정 조각을 한곳으로 모으는 해결 도구임을 보여준다. |
| 화면 구성 | 스마트폰이 중앙 정면에 나타나고 종이, 포스트잇, 체크리스트, 홀로그램 카드가 곡선을 그리며 화면 중심으로 빨려 들어간다. |
| 내레이션 또는 카피 | 화면 카피 없음 / 내레이션 `모두가 모~두 정리해줄게!` |
| 사용 도구와 목적 | ChatGPT 이미지 생성·Ideogram: 스마트폰과 MODU 로고 기준 이미지 / Google Flow: 흡수·입자 변환 모션 |
| 출력 결과 요약 | 현실의 혼란이 디지털 입자로 바뀌어 앱 안으로 들어가면서 문제와 해결 장면이 자연스럽게 연결되었다. |
| 결과 파일명 | `scene02_modu_intake_keyvisual.png` / `scene02_modu_intake_motion.mp4` |

### 입력 프롬프트 - 이미지 생성

```text
Use the official MODU logo image as the fixed brand identity reference. Create a complete smartphone upright in the center of the frame, full front view, entire phone visible, straight-on angle. Surround the phone with floating elements from Scene 1: large blue and pink paper sheets, yellow sticky notes, translucent cyan holographic cards, checklist symbols, calendar fragments, document pieces, and glowing notification particles. Keep the phone screen mostly dark and minimal. Show the official MODU logo at the top and a circular digital intake point glowing in neon blue and neon pink in the center. Do not reveal the final dashboard UI.
```

### 입력 프롬프트 - 영상 변환

```text
2-second commercial transition shot. Keep the smartphone centered and upright. Floating papers, sticky notes, checklist fragments, calendar pieces, holographic task cards, and notification particles bend into curved streams toward the center of the smartphone screen. As each element approaches the screen, it transforms into tiny neon cyan and pink particles and is absorbed into the glowing intake point. Do not reveal calendar UI, schedule cards, bottom navigation, or completed dashboard.
```

---

## 씬 3. 일정 자동 정리 - 최종 UI 공개


| 필수 항목 | 내용 |
|---|---|
| 씬 번호 / 길이 | 씬 3 / 약 2.7초 |
| 목표 메시지 | 일정과 할 일이 MODU의 카드형 대시보드에 자동으로 정리된다는 기능적 가치를 전달한다. |
| 화면 구성 | 스마트폰 정면 화면에 MODU 로고, `오늘`, 주간 캘린더와 일정 카드가 나타나고 네온 입자가 UI 요소를 활성화한다. |
| 내레이션 또는 카피 | 화면 카피 없음 / 내레이션 `일정, 과제, 약속까지 한눈에.` |
| 사용 도구와 목적 | Ideogram·ChatGPT 이미지 생성: 최종 앱 UI 기준 이미지 / Google Flow: 카드 글로우, 체크 활성화, 입자 확산 모션 |
| 출력 결과 요약 | 복잡한 정보가 정돈된 UI로 변환되어 앱의 핵심 기능이 시각적으로 드러났다. |
| 결과 파일명 | `scene03_dashboard_reference.png` / `scene03_dashboard_activation.mp4` |

### 입력 프롬프트 - 앱 UI 고정

```text
Use the MODU app UI reference image as the fixed final interface template. Preserve the complete smartphone presentation and app layout as closely as possible. Keep the same top MODU header, “2026 7월” label, large “오늘” title, weekly calendar row with “월 화 수 목 금 토 일” and dates 4 to 10, neon cyan highlight on Saturday 9, four stacked schedule cards, highlighted meeting card, and bottom navigation bar with glowing plus button. Do not redesign, rearrange, simplify, replace, or invent a different app interface.
```

### 입력 프롬프트 - 영상 변환

```text
3-second final MODU UI activation and reveal shot. Keep the complete smartphone centered, fully visible, upright, and straight-on. Preserve the official MODU logo, all Korean UI text, weekly calendar, dates, schedule card positions, icons, profile avatars, and bottom navigation exactly as shown. Use neon cyan and pink particles only to activate and illuminate the existing UI. The light travels across the calendar, reinforces Saturday 9, illuminates the schedule cards, highlights the meeting card, and gently pulses the bottom plus button once.
```

---

## 씬 4. 브랜드 각인 - 엔딩 카드


| 필수 항목 | 내용 |
|---|---|
| 씬 번호 / 길이 | 씬 4 / 약 2.7초 |
| 목표 메시지 | 정리된 하루의 결과를 MODU 로고와 엔딩 카피로 연결해 브랜드를 기억하게 한다. |
| 화면 구성 | 다크 네이비·딥 퍼플 회로 배경 위에 MODU 로고가 크게 나타나고 마지막에 `나의 하루를 한눈에.`가 표시된다. |
| 내레이션 또는 카피 | 화면 `나의 하루를 한눈에.` / 내레이션 `모두.` |
| 사용 도구와 목적 | Ideogram·ChatGPT 이미지 생성: 로고 엔딩 기준 이미지 / Google Flow: 입자·글로우 모션 / CapCut: 한글 엔딩 카피 입력 |
| 출력 결과 요약 | 마지막 약 3초 동안 브랜드명과 핵심 효익이 함께 노출되어 광고의 종결점이 분명해졌다. |
| 결과 파일명 | `scene04_modu_endcard.png` / `scene04_modu_endcard_motion.mp4` |

### 입력 프롬프트 - 이미지 생성

```text
Use the official MODU logo image as the highest-priority fixed brand identity reference. Preserve the wordmark closely. Create a final premium brand end card for the MODU AI productivity planner app. Place the official MODU wordmark prominently in the center of the frame where the smartphone stood in Scene 3. Preserve the dark navy and deep purple digital circuit-board background, purple glow on the left, blue glow on the right, and reflective grid floor. Leave a clean area below the logo for the Korean ending copy to be added later in CapCut. Do not generate Korean text inside the image.
```

### 입력 프롬프트 - 영상 변환

```text
3-second premium MODU brand end-card animation. Keep the official MODU logo centered, sharp, readable, and structurally unchanged throughout the shot. A faint residual phone-shaped neon aura and cyan-pink particles fade behind the logo. Add one subtle neon blue and pink glow pulse around the fixed MODU wordmark. Leave the area below the logo clean for the Korean ending copy added in CapCut.
```

---

## 8. 프롬프트 수정 전·후 기록

### 개선 대상: 씬 1 문제 제시 방식

**수정 전 의도**  
디지털 일정 카드와 알림창이 화면에 떠다니는 추상적인 '할 일 폭주' 장면을 만들고자 했다.

```text
chaotic digital task overload scene for a futuristic AI productivity planner app advertisement, many floating schedule cards, calendar reminders, notification popups, checklist icons, dark navy and deep purple background, neon blue and neon pink highlights
```

**발생한 문제**

- 씬 1부터 앱 UI와 비슷한 디지털 카드가 중심이 되어 씬 3의 해결 장면과 역할이 겹쳤다.
- 사용자가 실제로 겪는 책상, 서류, 노트북, 알림의 혼란이 부족해 공감도가 낮았다.
- 문제 제시와 해결 장면의 대비가 약했다.

**수정 후 프롬프트**

```text
chaotic everyday life scene, overwhelmed young adult, messy desk, laptop, planner, sticky notes, calendar page, coffee cup, resume papers, ringing smartphone, dark navy and deep purple environment, neon blue and neon pink lighting accents, subtle cyberpunk atmosphere
```

**수정 이유와 결과**

현실적인 사물과 인물의 압박감을 추가하되 네온 색상은 유지했다. 그 결과 씬 1은 '복잡한 일상', 씬 2는 'MODU로 전환', 씬 3은 '정리된 UI', 씬 4는 '브랜드 각인'으로 역할이 분리되었다.

### 추가 제작 수정: TTS 발음과 엔딩 카피

- 초기 대본의 영문 `MODU`가 `엠오디유`로 읽혀 음성 입력을 한글 `모두`로 변경했다.
- 발랄한 강조를 위해 TTS 입력에는 `모오오두`를 사용했다.
- 엔딩에 두 문장을 동시에 넣지 않고, 문제 카피 `할 일 폭주?`는 씬 1에, 효익 카피 `나의 하루를 한눈에.`는 씬 4에 배치했다.
- 결과적으로 음성 발음이 자연스러워지고 엔딩 화면의 정보 밀도가 낮아졌다.

---

## 9. 오디오 기획과 최종 편집

### Suno BGM 프롬프트

```text
10-second upbeat futuristic electronic pop instrumental for an AI productivity app advertisement, bright digital synth, clean tech mood, playful and energetic, neon cyberpunk feeling, suitable for a young female voice-over, short commercial jingle, no lyrics, no vocals.
```

### 최종 내레이션 대본

```text
할 일이 너무 많아?
모두가 모~두 정리해줄게!
일정, 과제, 약속까지 한눈에.
모두.
```

### 편집 원칙

- 내레이션을 중심으로 두고 BGM은 약 `-18dB~-24dB` 범위로 낮춰 사용했다.
- 컷 길이는 최종 영상 흐름에 맞춰 약 2.3초, 2.3초, 2.7초, 2.7초로 조정했다.
- 씬 1과 씬 4의 핵심 한글 카피는 CapCut에서 직접 입력해 오탈자와 생성 왜곡을 방지했다.
- CapCut은 컷 연결, 자막, 간단한 오디오 레벨 조정, H.264/AAC 출력에만 사용했다.

---

## 10. 과제 요구사항 최종 체크

| 요구사항 | 반영 내용 | 상태 |
|---|---|---|
| 브랜드·타깃·톤앤매너·USP 정의 | MODU 브랜드 아이덴티티에 명시 | 완료 |
| 광고 목적과 핵심 메시지 1문장 | 브랜드 인지 목적과 핵심 메시지 명시 | 완료 |
| 모든 씬의 필수 필드 | 번호, 길이, 목표, 화면, 카피, 도구, 프롬프트, 결과 요약, 파일명 포함 | 완료 |
| 프롬프트 수정 전·후 | 씬 1 개선 로그와 수정 이유·결과 기록 | 완료 |
| 이미지 생성 AI 1종 이상 | Ideogram, ChatGPT 이미지 생성 | 완료 |
| 비디오 생성 AI 1종 이상 | Google Flow | 완료 |
| 오디오 생성 AI 1종 이상 | Suno | 완료 |
| AI 시각·청각 요소 포함 | 최종 MP4에서 확인 | 완료 |
| 10초 이내 | 10.000초 | 완료 |
| 문제-전환-해결 구조 | 4씬 서사로 구성 | 완료 |
| 마지막 3~5초 브랜드 장치 | MODU 로고와 엔딩 카피 노출 | 완료 |
| 대체 도구 준비 | 이미지·비디오·BGM·TTS별 대안 기록 | 완료 |
| 생성형 AI 소스 중심 | 이미지·모션·BGM·내레이션을 AI로 제작 | 완료 |
| 통합 편집 범위 제한 | CapCut을 컷·자막·오디오 조정·인코딩에 사용 | 완료 |

---

## 11. 출처 표기와 최종 파일명

```text
본 영상의 AI 음성 내레이션은 네이버 클로바더빙을 활용하여 제작하였습니다.
```

최종 제출 파일은 아래와 같이 정리한다.

```text
MODU_storyboard_shinuiryeong.pdf
MODU_brand_ad_shinuiryeong_final_10s.mp4
```

작업 증빙용 원본:

```text
MODU_storyboard_final_shinuiryeong.md
```
