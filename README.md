# SK하이닉스 브랜드 광고 스토리보드 (최종)

## 1. 브랜드 아이덴티티

- **브랜드명**: SK hynix
- **타겟**: 일반 대중 (전 연령, 기술에 막연한 관심이 있는 소비자층)
- **톤앤매너**: 밝고 명확함, 확신에 찬 미래지향적 톤, 역동적이고 에너지 있는 하이테크
- **USP**: 우리가 매일 만지는 스마트폰·AI 서비스·클라우드 뒤에는 SK하이닉스의 메모리 반도체가 있다 — "세상을 앞으로 나아가게 하는 기술"
- **광고 목적**: 브랜드 인지도 향상 (일반 대중이 "SK하이닉스 = 미래를 만드는 기술 리더"로 인식하게 만들기)
- **핵심 메시지(한 문장)**: "세상의 속도를, 하이닉스가 앞당깁니다."

---

## 2. 스토리라인 구조

**구조 유형**: 밝고 확신에 찬 미래 선언 — "기술이 만드는 변화" (기승전결 변형)

- 도입: 역동적으로 빠르게 흐르는 데이터/빛 (기술의 에너지와 속도감)
- 전환: 데이터가 하나로 모이며 선명하고 자신감 있는 형태(인물/메시지)로 수렴
- 결말: 밝은 브랜드 로고 + 명확한 슬로건으로 마무리

마지막 3초 구간(씬3)에 브랜드명(SK hynix 자막) + 슬로건 노출 → 요구사항 충족. 추가로 씬2 립싱크 대사에도 브랜드명("하이닉스")을 포함시켜, 청각(씬2)과 시각(씬3)으로 브랜드를 이중 노출하는 구조로 설계함.

> 최종 영상 길이는 각 씬의 자연스러운 생성 결과(3초+2초+3초)에 따라 총 8초로 확정됨. 요구사항(10초 이내) 충족.

---

## 3. 씬 구성

### 씬 1 — Intro (0:00-0:03, 3초)

- **목표 메시지**: 세상은 지금도 빠르게, 힘있게 앞으로 나아가고 있다
- **화면 구성**: 밝은 배경 위로 빠르고 힘차게 흐르는 빛의 입자, 선명한 회로 패턴, 속도감 있는 데이터 스트림 / 텍스트 없음
- **내레이션(카피)**: (내레이션 없음, 경쾌하고 상승감 있는 사운드로 시작)
- **사용 도구 및 목적**:
  - 이미지 생성: Adobe Firefly (밝고 선명한 데이터/회로 키비주얼 생성)
  - 비디오 변환: Kling AI (빛 입자가 빠르게 흐르는 역동적 모션 부여)
  - 오디오: Suno (경쾌하고 상승감 있는 신스/비트 사운드)
- **입력 프롬프트(초안)**: `abstract fast-flowing data particles, bright vivid blue and white circuit lines on light background, dynamic energetic motion, high detail, confident futuristic tech aesthetic, 8k`
- **출력 결과 요약**: 밝은 흰색 배경에 블루 톤 데이터 입자가 역동적으로 흐르는 3초 영상 확보. Kling AI 워터마크가 우측 하단에 노출되어 편집 단계에서 확대(크롭)로 제거함
- **파일명**: scene01_keyvisual.png / scene01_motion.mp4

---

### 씬 2 — Transformation + 립싱크 발화 (0:03-0:05, 2초) 🔹보너스1 적용

- **목표 메시지**: 흩어진 데이터가 모여 "사람"이 되고, 그 사람이 자신감 있게 브랜드 메시지를 선언한다 (기술 → 사람의 연결고리)
- **화면 구성**: 밝은 빛의 입자들이 빠르게 모여들어 가상의 스타일화된 인물(실존 인물 아님, 선명하고 밝은 글로우 소재의 얼굴)이 형성되고, 그 인물이 카메라를 정면으로 보며 힘있게 대사를 말함 / 텍스트 없음
- **대사(발화, 립싱크 대상)**: "세상의 속도를, 하이닉스가 앞당깁니다"
- **자막 처리(최종 편집)**: 대사와 동일한 텍스트를 화면 자막으로 병기, Canva **"또렷하게(Clarify)"** 애니메이션 적용 — 텍스트가 선명하게 초점이 맞춰지며 등장하는 효과로, 발화 임팩트와 브랜드 메시지 각인을 동시에 강화
  - 색상 디테일: "세상의", "앞당깁니다"는 흰색 / **"속도"는 파란색**(속도감·기술 이미지 강조) / **"하이닉스"는 주황색**(브랜드명 시각적 강조) / 전체 글자 테두리는 검정색으로 처리하여 밝은 배경 위에서도 가독성 확보
- **사용 도구 및 목적**:
  - 이미지 생성: Adobe Firefly (데이터 입자로 이루어진 밝고 선명한 인물 얼굴 키비주얼)
  - 음성 생성: ElevenLabs (밝고 확신에 찬 톤의 보이스, 대사 음성 파일 선(先)생성 — 립싱크 도구에 입력하기 위해 오디오를 먼저 만들어야 함)
  - 립싱크: Kling AI 립싱크 기능 채택 (※ 최초 HeyGen으로 시도했으나 다운로드 단계에서 유료 결제 요구로 막혀, 이미 계정이 있던 Kling AI 립싱크 기능으로 대체함 — "도구 접근성 대응" 실사례 2)
  - 비디오 변환(배경 모션): Kling AI (입자가 힘있게 수렴하는 모션)
- **입력 프롬프트(최종, 이미지)**: `portrait of a confident Korean man, natural human facial features clearly visible, front-facing, bright clean white background, professional studio lighting, high detail, photorealistic, neutral confident expression, no overlay, no glow effect, no particle effects` (※ 최초 프롬프트에서 수정됨 — 4장 "프롬프트 수정 전/후 기록" 참고)
- **입력 프롬프트(음성, ElevenLabs 대사 텍스트)**: "세상의 속도를, 하이닉스가 앞당깁니다" (밝고 힘있는 톤 지정)
- **출력 결과 요약**: 한국인 남성이 "세상의 속도를, 하이닉스가 앞당깁니다" 대사를 자연스럽게 발화하는 2초 립싱크 영상 확보. HeyGen에서 1차 시도했으나 유료 결제 요구로 Kling AI로 재시도, Kling AI 워터마크도 우측 하단에 노출되어 편집 단계에서 확대(크롭)로 제거함
- **파일명**: scene02_face.png / scene02_voice.mp3 / scene02_lipsync.mp4

> ⚠️ 제작 순서 주의: 립싱크는 반드시 **음성 파일을 먼저 생성 → 얼굴 이미지 생성 → 두 소스를 립싱크 도구에 입력**하는 순서로 진행. 순서가 바뀌면 싱크 정확도가 떨어짐.

---

### 씬 3 — Brand Reveal (0:05-0:08, 3초)

- **목표 메시지**: 브랜드 인지 + 명확한 메시지 각인
- **화면 구성**: 밝은 배경에 SK hynix 로고가 선명한 빛으로 힘있게 형성되며 등장, 슬로건 텍스트가 또렷하게 등장
- **애니메이션 처리(최종 편집)**:
  - 영상 클립: Canva **"퀵 슬라이드(Quick Slide)"** 애니메이션 적용 — 로고 형성 비주얼이 속도감 있게 화면에 진입하며 "빠르게 앞당긴다"는 핵심 메시지를 시각적으로 강조
  - "SK hynix" 브랜드명 자막: Canva **"블록 쓸기(Block Wipe)"** 애니메이션 적용 — 블록 단위로 채워지며 로고가 드러나는 효과로, 브랜드명 등장에 힘있고 명확한 인상을 부여
  - 색상 디테일: **"SK"는 빨간색, "hynix"는 주황색**으로 적용하여 실제 SK hynix 공식 로고 색상 체계와 일치시킴 — 추상적 블루/화이트 톤의 배경 비주얼 위에 실제 브랜드 컬러를 정확히 노출시켜, 브랜드 인지 요건(로고/브랜드명)을 시각적으로 명확하게 충족
- **내레이션(카피)**: "SK hynix — 세상을 앞당기는 기술" (텍스트 카피로도 병행)
- **사용 도구 및 목적**:
  - 이미지 생성: Canva AI (※ Adobe Firefly 일일 생성 제한으로 대체 도구 사용 — "도구 접근성 대응" 실사례. 로고 주변 밝은 광원 효과 키비주얼)
  - 비디오 변환: Kling AI (로고가 빠르고 선명하게 형성되는 애니메이션)
  - 오디오: 씬1 배경음악 트랙을 전체 영상에 걸쳐 재사용 (클라이맥스 구간을 씬3에 배치)
  - 편집: Canva (로고/슬로건 텍스트 오버레이, 자막)
- **입력 프롬프트(최종)**: `bright glowing abstract logo shape formed from blue and white light particles, clean bright white background (not dark), vivid electric blue color palette, confident and dynamic brand reveal, high-tech minimal, no orange, no fire colors, no dark background` (※ 최초 프롬프트에서 색상 문제로 수정됨 — 4장 참고)
- **출력 결과 요약**: 밝은 흰색 배경에 블루 톤 입자가 빠르게 응집되어 로고 형태를 이루는 3초 영상 확보. Kling AI 워터마크가 우측 하단에 노출되어 편집 단계에서 확대(크롭)로 제거함
- **파일명**: scene03_keyvisual.png / scene03_motion.mp4 (최종 통합본은 8장 "최종 산출물" 참고)

---

## 4. 프롬프트 수정 전/후 기록

### 사례 1 — 씬 2 (얼굴 이미지, Adobe Firefly)

- **수정 전 의도**: 데이터 입자가 얼굴 전체를 뒤덮은 형태로, "데이터 → 사람"으로 변환되는 과정을 한 장의 이미지에 압축해서 표현하고자 함
  - 프롬프트: `bright glowing data particles forming a stylized human face, vivid light texture, front-facing, confident expression, bright blue and white light, energetic, high detail`
- **문제**: 결과물이 사람보다는 외계적/로봇 같은 인상을 줌. 파티클이 얼굴 전체(눈, 코, 입 주변)를 덮으면서 인물이라기보다 SF 캐릭터처럼 보였고, 배경도 밝은 톤 대신 어두운 우주/사이버 배경으로 나옴. 이렇게 되면 다음 단계인 립싱크 도구가 입 모양을 정확히 인식하기 어려울 위험도 있었음
- **수정 후 변경**: "얼굴 자체는 자연스러운 실사 인물로 두고, 파티클/빛 효과는 완전히 제거"하는 방향으로 프롬프트를 재설계. 대신 파티클이 모여 얼굴이 형성되는 연출은 정지 이미지가 아니라 다음 단계(Kling AI 영상 변환)의 모션으로 옮겨서 표현하기로 결정
  - 최종 프롬프트: `portrait of a confident Korean man, natural human facial features clearly visible, front-facing, bright clean white background, professional studio lighting, high detail, photorealistic, neutral confident expression, no overlay, no glow effect, no particle effects`
- **결과 변화**: 자연스러운 한국인 남성 인물 사진으로 전환됨. 밝은 흰색 배경 확보, 입 주변이 뚜렷하게 보여 립싱크 인식률도 개선됨. "이미지는 깔끔하게, 연출 효과는 영상 단계에서"라는 역할 분리 원칙을 이후 작업에도 적용함

### 사례 2 — 씬 3 (로고 배경 이미지, Canva AI — Adobe Firefly 일일 생성 제한으로 대체 도구 사용)

- **수정 전 의도**: 밝고 확신에 찬 브랜드 톤에 맞는 블루/화이트 계열의 로고 형성 비주얼을 기대함
  - 프롬프트: `bright glowing logo formation from light particles on light background, confident and dynamic brand reveal, vivid lighting, clean, premium futuristic tech feel`
- **문제**: Canva AI가 "premium tech feel"이라는 표현을 오렌지/파이어 톤의 어두운 배경으로 해석함. 브랜드 톤(밝은 블루/화이트)과 전혀 다른 색감이 나와 씬1, 씬2와 색감 통일성이 깨짐
- **수정 후 변경**: 색상을 프롬프트에 명시적으로 지정하고, 원치 않는 색상(오렌지/어두운 배경)을 네거티브 형태로 직접 배제
  - 최종 프롬프트: `bright glowing abstract logo shape formed from blue and white light particles, clean bright white background (not dark), vivid electric blue color palette, confident and dynamic brand reveal, high-tech minimal, no orange, no fire colors, no dark background`
- **결과 변화**: 밝은 흰색 배경에 블루 톤 입자로 응축된 로고 형태 비주얼을 확보. 씬1, 씬2와 색감이 통일되어 전체 영상의 일관성이 개선됨. 이 경험을 통해 색감처럼 브랜드 톤에 직결되는 요소는 추상적 표현("premium", "clean")보다 구체적 색상명과 네거티브 프롬프트를 함께 써야 의도한 결과를 안정적으로 얻을 수 있다는 점을 확인함

---

## 5. 사용 도구 목록 (요약)

| 역할 | 메인 도구 | 대체 도구(대기열/크레딧 이슈 대비) |
|---|---|---|
| 이미지 생성 | Adobe Firefly | Canva AI, Midjourney |
| 비디오 생성/변환 | Kling AI | Runway, Luma |
| 오디오(BGM/효과음) | Suno | Firefly 오디오 |
| 내레이션(TTS) | ElevenLabs | Canva TTS |
| 립싱크 | HeyGen | Kling AI 립싱크 |
| 통합 편집(컷/자막/비율 조정) | Canva | CapCut |

> 참고: 생성 도구(Kling AI 등)의 무료 플랜 특성상 씬1·씬2·씬3 영상 클립 모두에 워터마크가 삽입되어, 최종 통합 편집(Canva) 단계에서 각 클립을 5~8% 확대(크롭)하여 워터마크를 프레임 밖으로 제거함. 이는 컷 편집 범위 내 기본적인 리프레이밍으로, AI 생성물 자체를 조작하는 것은 아님.

---

## 6. 보너스2 — 동일 스토리보드, 다른 도구로 재제작

씬 1과 씬 3의 이미지/비디오 파트를 다른 도구로 교차 재제작하여 결과를 비교한다.

### 씬 1 — 재제작 버전 (도구 교체)

- **원본 도구**: Adobe Firefly (이미지) + Kling AI (비디오)
- **교체 도구**: (이미지는 기존 scene01_keyvisual.png 재사용) + Runway Gen-4 Turbo (비디오)
- **동일 프롬프트 사용**: `abstract fast-flowing data particles, bright vivid blue and white circuit lines on light background, dynamic energetic motion, high detail, confident futuristic tech aesthetic, 8k`
- **비교 관점**: 입자/회로 디테일 표현력, 색감 차이, 모션 자연스러움
- **파일명**: scene01_keyvisual.png (재사용) / scene01_motion_v2_runway.mp4
- **결과 비교 기록**: Kling AI는 프롬프트의 "fast flowing energetic motion"을 입자가 빠르게 흐르는 역동적인 모션으로 해석한 반면, Runway(Gen-4 Turbo)는 동일 프롬프트를 천천히 줌인되는 카메라 무브먼트로 해석함. "dynamic camera push-in" 문구에 대한 두 모델의 가중치 해석 차이로 추정됨. 브랜드 톤(밝고 힘있는 느낌)에는 Kling 버전이 더 적합하다고 판단하여 **최종 영상은 Kling 버전을 채택**함. (참고: Runway 버전은 최소 생성 길이가 5초로, Kling의 3초 옵션과 도구별 스펙 차이도 확인됨)

### 씬 3 — 재제작 버전 (선택사항, 미실시)

씬 1의 재제작만으로 보너스2 최소 요건("1~2개 씬")을 충족한다고 판단하여, 시간 관계상 씬 3 재제작은 진행하지 않음. 아래는 시도할 경우의 계획으로 남겨둠.

- **원본 도구**: Canva AI (이미지) + Kling AI (비디오)
- **교체 후보 도구**: Midjourney 또는 Adobe Firefly (이미지) + Runway 또는 Luma (비디오)
- **비교 관점(예정)**: 로고 형성 애니메이션의 자연스러움, 브랜드 프리미엄 톤 재현도

---

## 7. 보너스3 — 플랫폼별 화면 비율 버전 제작

동일 스토리보드/소스를 기반으로 3가지 비율 버전을 제작한다.

| 비율 | 용도 | 해상도 | 편집 시 고려사항 |
|---|---|---|---|
| 16:9 | 유튜브 | 1920x1080 | 원본 구도 그대로 사용 (기준 버전) |
| 9:16 | 숏폼/릴스/틱톡 | 1080x1920 | 핵심 피사체(입자 중심/얼굴/로고)가 세로 프레임 중앙에 오도록 크롭 또는 재구성. 특히 씬2 얼굴, 씬3 로고가 잘리지 않게 주의 |
| 1:1 | 피드(인스타그램 등) | 1080x1080 | 좌우 여백 최소화, 중앙 정렬 구도로 크롭 |

- **작업 방식**: 이미지/비디오 생성 시 가능하면 각 비율로 별도 생성하거나, 16:9 원본을 기준으로 Canva/CapCut에서 크롭·리프레이밍
- **파일명 규칙**: `SKhynix_ad_16x9.mp4` / `SKhynix_ad_9x16.mp4` / `SKhynix_ad_1x1.mp4`

---

## 8. 최종 산출물 파일 목록

**개별 씬 생성물**
- 씬1: `scene01_keyvisual.png`, `scene01_motion.mp4`, `scene01_bgm_full.mp3` (전체 영상 배경음악으로 재사용)
- 씬2: `scene02_face.png`, `scene02_voice.mp3`, `scene02_lipsync.mp4`
- 씬3: `scene03_keyvisual.png`, `scene03_motion.mp4`

**보너스2 비교용**
- `scene01_motion_v2_runway.mp4` (Runway Gen-4 Turbo 재제작 버전)

**최종 통합 영상 (제출용)**
- `SKhynix_ad_16x9.mp4` — 기준 버전, 1920x1080, 8초
- `SKhynix_ad_9x16.mp4` — 숏폼/릴스용, 1080x1920 (보너스3)
- `SKhynix_ad_1x1.mp4` — 피드용, 1080x1080 (보너스3)

## 9. 진행 현황 체크리스트

| 항목 | 상태 |
|---|---|
| 브랜드/캠페인 정의 | ✅ 완료 |
| 스토리보드 문서화 (씬별 필수 필드) | ✅ 완료 |
| 프롬프트 수정 전/후 기록 (최소 1개 이상) | ✅ 완료 (2개 사례) |
| 이미지/비디오/오디오 생성 도구 각 1종 이상 사용 | ✅ 완료 |
| 최종 영상 10초 이내 | ✅ 완료 (8초) |
| 서사/메시지 구조 | ✅ 완료 (도입-전환-결말 구조 + 청각·시각 이중 브랜드 노출) |
| 마지막 3~5초 브랜드 인지 장치 | ✅ 완료 (씬3 브랜드명 자막) |
| 보너스1 — 립싱크 | ✅ 완료 |
| 보너스2 — 다른 도구 재제작 (1~2개 씬) | ✅ 완료 (씬1) |
| 보너스3 — 화면비율 버전 (2개 이상) | ✅ 완료 (16:9 / 9:16 / 1:1, 총 3개) |
