# Library Manager

<p align="center">
  <img src="assets/icon.png" width="128" height="128" alt="Library Manager Icon">
</p>

**[한국어](#한국어) | [English](#english)**

---

# 한국어

**만화 라이브러리 관리 도구** - 폴더명 기반 자동 메타데이터 인식, 태그/평점 관리, 이미지 번역 기능을 제공하는 데스크톱 앱

## ✨ 주요 기능

### 📚 라이브러리 관리
- **자동 메타데이터 인식**: `[작가] 제목` 형식의 폴더명에서 작가와 제목을 자동 추출
- **썸네일 자동 생성**: 첫 번째 이미지를 기반으로 썸네일 생성
- **라이브러리 스캔**: 변경된 폴더만 스캔하는 증분 스캔 지원

### ⭐ 작품 관리
- **평점 시스템**: 1~5점 별점 부여
- **태그 관리**: 커스텀 태그 추가/편집/삭제
- **카운트 기능**: 열어본 횟수 자동 기록
- **시리즈 그룹핑**: 여러 작품을 하나의 시리즈로 묶어서 관리
- **일괄 태그 편집**: 여러 작품 선택 후 태그 일괄 추가/삭제

### 🔍 필터 & 정렬
- 제목/작가 검색, 태그 필터, 평점 필터, 시리즈 필터
- 정렬: 제목순, 작가순, 평점순, 열어본 횟수순, 랜덤

### 🌐 이미지 번역
- **Papago API**: 네이버 클라우드 플랫폼 이미지 번역
- **Gemini API**: Google Gemini 기반 OCR + 번역
- 전체 페이지 일괄 번역, 번역본 자동 저장

### 🌍 다국어 지원
한국어, English, 日本語, 简体中文, 繁體中文, Français, Deutsch, Español, Italiano, Português, Русский, Tiếng Việt, Bahasa Indonesia

---

## 💻 시스템 요구사항

| 플랫폼 | 최소 요구사항 |
|--------|--------------|
| Windows | Windows 10 이상 (x64) |
| macOS | macOS 10.15 이상 |

---

## 📂 라이브러리 구조

```
라이브러리 폴더/
├── [작가A] 작품제목1/
│   ├── 001.jpg
│   └── ...
├── [작가B] 다른작품/
└── 작품제목만있는폴더/    ← 작가: "Unknown"
```

---

## 📝 무료 vs Pro

| 기능 | 무료 | Pro |
|------|:----:|:---:|
| 작품 수 제한 | 1,000개 | 무제한 |
| 기기 수 | 1대 | 3대 |

---

# English

**Manga Library Manager** - Desktop app with automatic metadata detection from folder names, tag/rating management, and image translation

## ✨ Features

### 📚 Library Management
- **Auto Metadata Detection**: Extracts author and title from folder names in `[Author] Title` format
- **Auto Thumbnail Generation**: Creates thumbnails from the first image
- **Incremental Scan**: Only scans changed folders

### ⭐ Item Management
- **Rating System**: 1-5 star ratings
- **Tag Management**: Custom tags with add/edit/delete
- **View Count**: Automatic tracking of open count
- **Series Grouping**: Group multiple works into a series
- **Batch Tag Editing**: Add/remove tags for multiple items at once

### 🔍 Filter & Sort
- Title/author search, tag filter, rating filter, series filter
- Sort by: title, author, rating, view count, random

### 🌐 Image Translation
- **Papago API**: Naver Cloud Platform image translation
- **Gemini API**: Google Gemini-based OCR + translation
- Batch translation, auto-save translated images

### 🌍 Multi-language Support
한국어, English, 日本語, 简体中文, 繁體中文, Français, Deutsch, Español, Italiano, Português, Русский, Tiếng Việt, Bahasa Indonesia

---

## 💻 System Requirements

| Platform | Minimum |
|----------|---------|
| Windows | Windows 10+ (x64) |
| macOS | macOS 10.15+ |

---

## 📂 Library Structure

```
Library Folder/
├── [AuthorA] Title1/
│   ├── 001.jpg
│   └── ...
├── [AuthorB] AnotherWork/
└── TitleOnlyFolder/    ← Author: "Unknown"
```

---

## 📝 Free vs Pro

| Feature | Free | Pro |
|---------|:----:|:---:|
| Item Limit | 1,000 | Unlimited |
| Devices | 1 | 3 |

---

## 📄 License

MIT License

## 🤝 Contact

Use the in-app inquiry feature or GitHub Issues.
