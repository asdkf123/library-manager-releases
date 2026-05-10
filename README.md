# 📚 Library Manager

**The Ultimate Desktop App for Managing Your Local Manga, Webtoon, and Novel Collections — now with mobile web access and a fully redesigned interface.**

[![Download](https://img.shields.io/badge/Download-Latest-blue?style=for-the-badge)](https://github.com/asdkf123/library-manager-releases/releases/latest)
[![Discord](https://img.shields.io/badge/Discord-Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/MbNWZNSVYR)
[![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-lightgrey?style=for-the-badge)](#-download--installation)

---

## ✨ Why Library Manager?

If you have your own collection of manga, webtoons, or novels stored locally, this app is built for you. Drop your folders in, and Library Manager indexes everything: parses `[Author] Title` patterns, detects encodings, generates thumbnails, and gives you a clean reading experience across desktop and mobile — without uploading a single file to a server.

---

## 🎨 Brand-New Interface (v5.1)

The entire app has been redesigned from the ground up.

- **Unified design system**: Sidebar, titlebar, dashboard, library grid, and viewers all share a consistent look.
- **Tuned for long sessions**: Carefully chosen colors and typography reduce eye strain during long reading sessions.
- **Status bar with at-a-glance signals**: Update notifications, sync status, and remote access state all live in a quiet corner of the window.
- **13 languages, fully translated**: Every screen, dialog, and tooltip in English, 한국어, 日本語, 中文(简体·繁體), Español, Deutsch, Français, Português, Русский, Bahasa Indonesia, Italiano, Tiếng Việt.

---

## 📱 Mobile Web Access (Remote)

Read your library from anywhere — your phone, tablet, or another computer — without leaving home.

- **One-click remote tunnel**: Enable remote access from settings, get a personal `your-name.librarymanager.app` URL.
- **Same library, mobile-optimized UI**: Browse series, jump straight into chapters, pick up reading where you left off.
- **No port forwarding, no router setup**: Works behind any home network or carrier NAT.
- **Stays on your machine**: Files are streamed from your PC on demand. Nothing is uploaded to the cloud.

---

## ✨ Core Features

### 📂 Universal Library Management

- **Manga**: Folders **and** archive files (`.zip`, `.cbz`) — read directly from archives, no extraction needed.
    - Auto-detects `[Author] Title` format from folder/file names.
    - Bulk tag and rating editing.
- **Webtoon**: `Series > Episode` folder structure with drag-and-drop episode reordering.
- **Novel**: TXT, EPUB, and PDF.
    - **Smart encoding detection** — never see broken text again. Korean (CP949), Japanese (Shift_JIS), Chinese, and Unicode are all handled automatically.

### 🌏 Real-time AI Image Translation

- **Gemini (Google) & Papago (Naver)** integration — translate manga and webtoon pages while you read.
- **Dual View** toggle: switch between original and translated versions instantly.
- **Bring your own key**: free with the Gemini Free Tier. No middleman, no markup.

### 🎨 Modern Viewers

- **Manga**: Two-page spread, continuous scroll, fit-to-width / fit-to-height. Streams from archives.
- **Webtoon**: Optimized vertical scrolling for long-strip content.
- **Novel**: Auto-bookmarks reading position. Customize fonts, line spacing, and themes.

### 💾 Privacy-First Data Handling

- **One-click backup & restore**: Library metadata, reading progress, thumbnails, ratings, and settings — all in a single `.zip`.
- **Local-only storage**: Everything lives on your machine in a SQLite database. No telemetry on your library contents, no cloud sync of files.
- **Move freely**: Reformat your PC, switch machines, or share with another device — restore from backup and you're back where you left off.

### 🔄 Smart Auto-Update

- **In-app update notifications** in the status bar — no intrusive popups.
- **7-day offline grace period** for license verification: keep reading even when you're disconnected.

---

## 💎 Free vs Pro

| Feature | Free | Pro |
| :--- | :---: | :---: |
| **Total Items** (Manga + Webtoon + Novel) | Max 500 | **Unlimited** |
| **Devices** | 1 | **Up to 3** |
| **Mobile Web Remote Access** | ✓ | ✓ |
| **AI Image Translation** | ✓ | ✓ |
| **Support** | Community | **Direct from developer** |

---

## 🚀 Download & Installation

| Platform | Download | Notes |
| :--- | :--- | :--- |
| **Windows** | [Download .exe](https://github.com/asdkf123/library-manager-releases/releases/latest) | Windows 10 / 11 (x64) |
| **macOS (Apple Silicon)** | [Download .dmg (M1/M2/M3)](https://github.com/asdkf123/library-manager-releases/releases/latest) | **Notarized** — runs without security warnings |
| **macOS (Intel)** | [Download .dmg (Intel)](https://github.com/asdkf123/library-manager-releases/releases/latest) | **Notarized** — runs without security warnings |

---

## 💬 Community

[![Discord](https://img.shields.io/badge/Discord-Official%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/MbNWZNSVYR)

Questions, feedback, or feature requests? Use the in-app **Contact** form or join the Discord. Issues are usually answered within a day.

---

<br><br><br>

---

# 📚 Library Manager (한국어)

**로컬 만화, 웹툰, 소설을 위한 최고의 데스크톱 관리 도구 — 모바일 웹 접근과 완전히 새로워진 인터페이스까지.**

[![Download](https://img.shields.io/badge/다운로드-최신버전-blue?style=for-the-badge)](https://github.com/asdkf123/library-manager-releases/releases/latest)
[![Discord](https://img.shields.io/badge/Discord-공식커뮤니티-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/MbNWZNSVYR)

---

## ✨ Library Manager가 필요한 이유

집에 만화·웹툰·소설을 모아두는 분들을 위한 앱입니다. 폴더만 던져 넣으면 `[작가] 제목` 패턴을 알아서 파싱하고, 인코딩을 감지하고, 썸네일을 생성합니다. 데스크톱과 모바일 어디서든 깨끗한 독서 경험을 제공하면서 **파일을 외부 서버에 단 한 장도 올리지 않습니다.**

---

## 🎨 새로워진 인터페이스 (v5.1)

앱 전체를 완전히 새로 디자인했습니다.

- **일관된 디자인 시스템**: 사이드바·타이틀바·대시보드·라이브러리 그리드·뷰어 모두 통일된 룩으로 정돈.
- **장시간 사용에 최적화**: 색상과 타이포그래피를 신중히 다듬어 오래 봐도 눈이 덜 피로하도록.
- **상태바 한눈에 보기**: 업데이트 알림, 동기화 상태, 원격 접속 상태가 창 모서리에 조용히 표시.
- **13개 언어 완전 적용**: 영어, 한국어, 일본어, 중국어(간체·번체), 스페인어, 독일어, 프랑스어, 포르투갈어, 러시아어, 인도네시아어, 이탈리아어, 베트남어 — 모든 화면, 다이얼로그, 툴팁까지.

---

## 📱 모바일 웹 접근 (원격 접속)

집에 켜둔 라이브러리를 외부에서 휴대폰·태블릿·다른 컴퓨터로 그대로 읽을 수 있습니다.

- **원클릭 원격 터널**: 설정에서 켜기만 하면 `내이름.librarymanager.app` 같은 개인 URL이 부여됩니다.
- **모바일 최적화 UI**: 같은 라이브러리를 폰 화면에 맞춰 깔끔하게. 시리즈 탐색, 챕터 바로 진입, 마지막 읽던 위치 이어보기까지.
- **포트포워딩·공유기 설정 불필요**: 가정용 인터넷이나 통신사 NAT 환경에서도 그대로 동작.
- **데이터는 PC에 그대로**: 모든 파일은 PC에서 필요할 때만 스트리밍됩니다. 클라우드에 올라가지 않습니다.

---

## ✨ 핵심 기능

### 📂 만능 라이브러리 관리

- **만화**: 일반 폴더 **그리고** 압축 파일(`.zip`, `.cbz`) 모두 지원 — 압축을 풀 필요 없이 바로 읽기.
    - `[작가] 제목` 형식의 폴더/파일을 자동 인식.
    - 태그·별점 일괄 편집.
- **웹툰**: `시리즈 > 에피소드` 폴더 구조에 특화. 드래그앤드롭으로 에피소드 순서 변경.
- **소설**: TXT, EPUB, PDF 지원.
    - **스마트 인코딩 감지** — 깨진 글자는 이제 그만. 한국어(CP949), 일본어(Shift_JIS), 중국어, 유니코드 모두 자동 처리.

### 🌏 AI 이미지 실시간 번역

- **Gemini (구글) & Papago (네이버)** 연동 — 만화·웹툰 이미지를 읽는 도중 번역.
- **듀얼 뷰**: 클릭 한 번으로 원본과 번역본을 토글.
- **개인 API 키 사용**: Gemini 무료 티어로 비용 부담 없이. 중간 마진 없이 직접.

### 🎨 빠르고 강력한 뷰어

- **만화**: 두 쪽 보기, 연속 스크롤, 너비 맞춤 / 높이 맞춤. 압축 파일 직접 스트리밍.
- **웹툰**: 긴 호흡의 웹툰을 위한 끊김 없는 세로 스크롤.
- **소설**: 읽던 위치 자동 저장. 폰트·줄간격·테마 커스터마이징.

### 💾 프라이버시 우선 데이터 관리

- **원클릭 백업·복구**: 라이브러리 목록, 읽기 기록, 썸네일, 별점, 설정까지 `.zip` 하나로 묶음.
- **로컬 전용 저장**: 모든 데이터는 PC의 SQLite에. 라이브러리 내용에 대한 텔레메트리도 없고, 파일 클라우드 동기화도 없음.
- **자유로운 이동**: PC를 포맷하든, 새 컴퓨터로 옮기든, 백업 파일 하나만 있으면 그대로 복원.

### 🔄 스마트 자동 업데이트

- **상태바 업데이트 알림** — 작업 흐름을 끊는 팝업 없음.
- **7일 오프라인 유예 기간**: 인터넷이 끊겨도 일정 기간 동안 그대로 사용 가능.

---

## 💎 Free vs Pro

| 기능 | Free | Pro |
| :--- | :---: | :---: |
| **라이브러리 통합 제한** (만화 + 웹툰 + 소설) | 총 500개 | **무제한** |
| **기기 사용** | 1대 | **최대 3대** |
| **모바일 웹 원격 접속** | ✓ | ✓ |
| **AI 이미지 번역** | ✓ | ✓ |
| **기술 지원** | 커뮤니티 | **개발자 직접 지원** |

---

## 💻 다운로드 및 설치

| 플랫폼 | 다운로드 | 비고 |
| :--- | :--- | :--- |
| **Windows** | [다운로드 .exe](https://github.com/asdkf123/library-manager-releases/releases/latest) | Windows 10 / 11 (x64) |
| **macOS (Apple Silicon)** | [다운로드 .dmg (M1/M2/M3)](https://github.com/asdkf123/library-manager-releases/releases/latest) | **Apple 공증 완료** — 보안 경고 없이 안전하게 실행 |
| **macOS (Intel)** | [다운로드 .dmg (Intel)](https://github.com/asdkf123/library-manager-releases/releases/latest) | **Apple 공증 완료** — 보안 경고 없이 안전하게 실행 |

---

## 💬 커뮤니티 & 피드백

[![Discord](https://img.shields.io/badge/Discord-입장하기-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/MbNWZNSVYR)

질문, 피드백, 기능 제안은 앱 내 **"문의하기"** 또는 공식 디스코드로. 보통 하루 안에 답변드립니다.

---
<p align="center">Made with ❤️ by Lodi Developer</p>
