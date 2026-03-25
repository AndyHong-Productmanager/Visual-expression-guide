# 🎬 AI Visual Prompt Master Guide

**AI 이미지/영상 생성을 위한 시각 용어 종합 가이드**

> 나노바나나, Flow, Midjourney, Runway, Kling, Sora 등에서 프롬프트를 쓸 때  
> "예쁘게 해줘" 대신 **정확한 용어 하나**가 결과물의 퀄리티를 결정한다.

---

## 이게 뭔가

바이브코딩으로 앱을 만들 듯, AI 이미지/영상도 "바이브 프롬프팅"으로 만드는 시대다.  
그런데 코딩에 변수명이 중요하듯, 프롬프트에도 **정확한 용어**가 중요하다.

이 가이드는 영화/사진 현장에서 실제로 쓰는 카메라 워크, 필름, 조명, 연출 용어를  
AI 프롬프트 관점에서 재정리한 것이다. 각 용어마다 **한국어 설명 + 영문 프롬프트 예시 + SVG 일러스트**를 포함한다.

## 포함된 내용

| 섹션 | 내용 | 용어 수 |
|------|------|---------|
| 샷 사이즈 | EWS, Wide, Medium, CU, ECU, Insert | 6종 |
| 카메라 앵글 | Eye Level, Low/High, Bird's Eye, Dutch, OTS | 6종 |
| 카메라 무브먼트 | Pan, Dolly, Orbit, Zoom + 7종 추가 | 11종 |
| 렌즈 & 초점 | Shallow DOF, Anamorphic, Macro, Wide Angle + 4종 | 8종 |
| 구도 | Rule of Thirds, Symmetry, Leading Lines, Frame in Frame + 4종 | 8종 |
| **필름 시뮬레이션** | Nostalgic Neg, Classic Neg, Portra 400, Ektar, CineStill 800T, Velvia, Gold, Tri-X | **8종** |
| **색보정** | Teal & Orange, Desaturated, High/Low Key, Bleach Bypass, Cross Process | **6종** |
| **조명** | Golden Hour, Blue Hour, Rembrandt, Neon, Window, God Rays, Rim, Hard | **8종** |
| **표정 / 감정** | 미소, 환한 웃음, 노려보기, 눈물, 공포, 사색, 수수께끼, 도전적 + 9종 | **17종** |
| **시선 · 자세 · 동작** | 정면 응시~허공 응시, 팔짱~콘트라포스토, 히어로 워크~슬로모션 | **29종** |
| **분위기 · 연출** | 멜랑콜리~호화로운, 미장센~키아로스쿠로, 감독 스타일 6명 | **25종** |
| **질감 · 환경 · 시대** | 피부 질감, 폭우~벚꽃, 빅토리안~사이버펑크~지브리 | **22종** |
| **합계** | | **150+ 용어** |

## 파일 구성

```
📁 ai-visual-prompt-guide/
├── AI_Visual_Prompt_Master_Guide.html   ← 전체 통합본 (이것만 봐도 됨)
├── Camera_Work_Terminology_Guide.html   ← 카메라 워크 (샷/앵글/무브먼트/렌즈/구도)
├── Film_Color_Lighting_Guide.html       ← 필름 시뮬레이션 + 색보정 + 조명
├── Visual_Expression_Guide.html         ← 표정 + 동작 + 분위기 + 연출 + 시대
├── Camera_Work_Terminology_Guide.docx   ← Word 버전 (카메라 워크)
├── Camera_Work_Terminology_Guide.md     ← Markdown 버전 (카메라 워크)
└── README.md
```

## 사용법

1. HTML 파일을 브라우저에서 연다
2. 원하는 분위기/구도에 해당하는 용어를 찾는다
3. 각 카드의 `PROMPT` 부분을 복사하거나 참고하여 프롬프트를 조합한다

### 조합 예시

```
medium close-up, low angle, shallow depth of field, anamorphic lens flare,
teal and orange color grading, Rembrandt lighting,
a confident businesswoman walking through a modern lobby
```

```
wide shot, dutch angle, shot on CineStill 800T, red halation,
neon cyberpunk lighting, rain-soaked street,
tracking shot through a neon-lit Tokyo alley at night
```

```
close-up, Fujifilm Nostalgic Negative, warm amber highlights,
natural window light, pensive expression, looking away,
a woman reading a letter in a sunlit vintage cafe
```

**용어를 레이어처럼 쌓으면 된다:**

```
[샷 사이즈] + [앵글] + [렌즈] + [필름/색보정] + [조명] + [표정] + [동작] + [분위기] + [피사체 묘사]
```

## 누구를 위한 건가

- AI 이미지/영상 생성 도구를 쓰는 **바이브코더**
- "cinematic"만 반복하다가 한계를 느낀 사람
- 프롬프트 하나로 퀄리티를 올리고 싶은 사람
- 영화/사진 용어를 체계적으로 정리하고 싶은 사람

## 만든 이유

바이브코딩 커뮤니티에서 AI 이미지/영상 만드는 분들이 늘어나고 있다.  
코드를 AI에게 시키듯 이미지도 AI에게 시키는 건데,  
프롬프트의 "어휘력"이 결과물의 천장을 결정한다.

영화과 전공이 아니어도, 이 가이드의 용어를 참조하면서 프롬프트를 쓰면  
**전문가 수준의 시각적 디렉션**이 가능하다.

## 기여

오류 발견이나 추가할 용어가 있으면 Issue 또는 PR 환영한다.

## License

MIT

---

**DOCTORMODU** · 2026.03  
바이브코딩하는의사들 커뮤니티
