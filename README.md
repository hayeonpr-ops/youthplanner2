# 📅 2026 경북프라이드기업 해외연수 일정표

> 독일 · 스위스 · 이탈리아 9일 | 공공기관·기업체 맞춤형 해외연수 일정표  
> 제작: **청년기획** — 맞춤형 해외연수 컨설팅

---

## 🌐 미리보기

| 모바일 | 태블릿 | PC |
|:---:|:---:|:---:|
| 탭 필터 + 카드형 일정 | 여백 확대 레이아웃 | 사이드바 + 2컬럼 |

📌 **GitHub Pages 배포 시 바로 사용 가능한 단일 HTML 파일입니다.**

---

## ✈️ 연수 개요

| 항목 | 내용 |
|---|---|
| 대상 | 경북프라이드기업 |
| 기간 | 2026년 11월 24일(화) ~ 12월 2일(수) · 9일간 |
| 방문 국가 | 🇩🇪 독일 · 🇨🇭 스위스 · 🇮🇹 이탈리아 |
| 기업방문 | 총 6개사 (히든챔피언 4개사 포함) |
| 박람회 | SPS 2026 — 뉘른베르크 국제 자동화 산업 박람회 |
| 항공편 | OZ 541 (인천→프랑크푸르트) / OZ 582 (밀라노→인천) |

---

## 🏭 기업방문 목록

| # | 기업명 | 분야 | 국가 | 도시 |
|:---:|---|---|:---:|---|
| ① | Koenig & Bauer | 인쇄기계 히든챔피언 | 🇩🇪 | 뷔르츠부르크 |
| ② | LEONI Group | 와이어링 히든챔피언 | 🇩🇪 | 뉘른베르크 |
| ③ | 메르세데스-벤츠 팩토리 | 자동차 제조 | 🇩🇪 | 진델핑엔 |
| ④ | KUKA Roboter GmbH | 산업용 로봇 히든챔피언 | 🇩🇪 | 아우크스부르크 |
| ⑤ | Logitech | IT 주변기기 히든챔피언 | 🇨🇭 | 로잔 |
| ⑥ | Brembo N.V. | 자동차 브레이크 전문 | 🇮🇹 | 베르가모 |

---

## 📁 파일 구조

```
📦 repository
 ┗ 📄 index.html      # 반응형 해외연수 일정표 (단일 파일)
 ┗ 📄 README.md       # 프로젝트 설명
```

> 외부 라이브러리 의존 없이 **단일 HTML 파일**로 동작합니다.  
> Google Fonts (Freesentation) 로드를 위한 인터넷 연결만 필요합니다.

---

## 🚀 사용 방법

### 로컬에서 열기
```bash
git clone https://github.com/{username}/{repo-name}.git
cd {repo-name}
# index.html 파일을 브라우저에서 열기
open index.html
```

### GitHub Pages 배포
1. 저장소 → **Settings** → **Pages**
2. Source: `Deploy from a branch`
3. Branch: `main` / `(root)` 선택 후 **Save**
4. 배포 완료 후 `https://{username}.github.io/{repo-name}/` 접속

---

## 📱 반응형 지원

| 브레이크포인트 | 화면 너비 | 레이아웃 |
|---|---|---|
| 모바일 | ~ 639px | 상단 헤더 고정 + 탭 필터 + 1열 카드 |
| 태블릿 | 640px ~ 959px | 여백·폰트 확대 |
| PC | 960px ~ 1199px | 좌측 사이드바 + 우측 콘텐츠 |
| 와이드 PC | 1200px ~ | 사이드바 290px + 최대 너비 920px |

---

## ✨ 주요 기능

- **탭/사이드바 필터** — 국가별(독일·스위스·이탈리아), 기업방문, 박람회 필터링
- **일별 접기/펼치기** — 카드 헤더 탭으로 토글, 전체 접기 버튼 제공
- **사이드바 자동 하이라이트** — 스크롤 위치에 따라 현재 일정 자동 활성화 (PC)
- **빠른 이동** — 사이드바 클릭 시 해당 일정으로 스크롤 + 카드 자동 펼침
- **항공·숙소 정보** — 항공편, 호텔 정보 배너로 시각화
- **기업 정보 카드** — 주소, 전화번호, 공식 홈페이지 링크 포함
- **식사 정보** — 조식·중식·석식 칩으로 구분 표시

---

## 🛠 기술 스택

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

- **프레임워크**: 없음 (Vanilla HTML/CSS/JS)
- **폰트**: [Freesentation](https://fonts.google.com/specimen/Freesentation) (Google Fonts)
- **외부 의존성**: 없음

---

## 📝 오타 수정 내역 (원본 PDF → 수정)

| 원본 | 수정 | 위치 |
|---|---|---|
| MARITIM FRANFURT HOTEL | MARITIM **FRANKFURT** HOTEL | 1일 숙소 |
| 프랑크프루트 | 프랑크**푸**르트 | 2일 이동 |
| 아우구스부르크 | 아우**크**스부르크 (Augsburg) | 4·5일 지역명 |
| gspitzstraße (KUKA 주소) | **Zug**spitzstraße | 기업 주소 |
| 성안나교회 | 성 **안나** 교회 | 4일 탐방 |
| 요새였떤 | 요새였**던** | 8일 설명 |

---

## ⚠️ 안내사항

- 상기 일정은 현지 사정에 의해 변경될 수 있습니다.
- 본 일정표는 경북프라이드기업 전용 자료입니다.

---

<div align="center">

**Made by [청년기획](https://)**  
공공기관·기업체 맞춤형 해외연수 컨설팅

</div>
