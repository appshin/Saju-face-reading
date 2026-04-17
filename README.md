[README.md](https://github.com/user-attachments/files/26806846/README.md)
# 觀相四柱 — AI 사주팔자

> 얼굴을 비추면 AI가 관상과 사주팔자를 풀이해 드립니다.

![HTML](https://img.shields.io/badge/HTML-single%20file-orange)
![License](https://img.shields.io/badge/license-MIT-green)

## 소개

카메라로 얼굴을 비추거나 사진을 업로드하면, AI가 전통 관상학과 사주팔자(四柱八字)를 기반으로 재미있는 운세 풀이를 생성해 주는 웹 앱입니다.

## 주요 기능

- **실시간 카메라** — 전면 카메라로 얼굴을 바로 촬영
- **사진 업로드** — 갤러리에서 얼굴 사진 선택
- **AI 관상 분석** — 이마, 눈, 코, 입, 턱 등 생김새 풀이
- **사주팔자 배정** — 년주·월주·일주·시주 (천간+지지) 생성
- **오행 분석** — 목(木)·화(火)·토(土)·금(金)·수(水) 균형 진단
- **종합운세** — 성격, 직업운, 재물운, 연애운, 건강운, 행운 정보

## 데모

GitHub Pages로 배포 후 접속:

```
https://<your-username>.github.io/<repo-name>/
```

## 사용 방법

1. 이 저장소를 클론하거나 포크합니다.
2. GitHub 저장소 **Settings → Pages → Source**를 `main` 브랜치로 설정합니다.
3. 배포된 URL에 접속하여 카메라를 켜거나 사진을 올린 뒤 **✦ 사주팔자 보기 ✦** 버튼을 누릅니다.

## 기술 스택

| 항목 | 내용 |
|------|------|
| 프론트엔드 | HTML / CSS / Vanilla JS (단일 파일) |
| AI 모델 | Claude Sonnet 4 (Anthropic API) |
| 카메라 | WebRTC (`getUserMedia`) |
| 폰트 | Noto Serif KR, Crimson Pro |

## 프로젝트 구조

```
.
└── index.html    ← 앱 전체 (별도 빌드 불필요)
```

## 주의사항

- 이 앱은 **오락 목적**으로 제작되었으며, 실제 역학·관상학적 근거와 무관합니다.
- Anthropic API 호출이 포함되어 있어, 브라우저에서 API에 접근 가능한 환경이 필요합니다.
- 카메라 사용 시 브라우저의 카메라 권한 허용이 필요합니다.

## 라이선스

MIT License
