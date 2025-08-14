# 📰 네이버 뉴스 크롤링 & 워드클라우드 분석

2025년 8월 4일부터 6일까지의 네이버 뉴스 데이터를 수집하고,  
워드클라우드 형태로 시각화한 프로젝트입니다.

---

## 📌 프로젝트 개요

- **목적**: 5대 대기업(삼성, LG, 현대차, SK, 롯데 등)의 뉴스 보도 동향을 수집하고 주요 키워드를 시각화
- **수집 기간**: 2025.08.04 ~ 2025.08.06
- **데이터 출처**: 네이버 뉴스 검색
- **사용 기술**:  
  - `Python`, `Selenium`, `Pandas`
  - `WordCloud`, `matplotlib`

---

## 🖥️ 주요 기능

- 날짜별 뉴스 크롤링 (기간 설정 가능)
- 기사 제목, 언론사, 요약, 네이버 뉴스 링크 수집
- 워드클라우드 시각화 생성
- 중복 기사 제거 로직 포함

---

## 🗂️ 파일 구조

| 파일명 | 설명 |
|--------|------|
| `naver_news_crawler.ipynb` | 네이버 뉴스 크롤링 및 워드클라우드 생성 코드 |
| `naver_news_date_range.csv` | 수집된 뉴스 데이터 (날짜별, 키워드별) |
| `wordcloud_filtered.png` | 생성된 워드클라우드 이미지 (빈도 기반) |

---

## 🖼️ 워드클라우드 예시

<img width="794" height="601" alt="Image" src="https://github.com/user-attachments/assets/d4000b7c-a8a3-43ad-a7cc-a4c6f5d6dadf" />

---

## ⚙️ 설치 라이브러리 (`requirements.txt`)

```txt
selenium
pandas
matplotlib
wordcloud

