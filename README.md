# 📚 Book Recommendation System
- PySpark와 MySQL을 활용한 도서 추천 시스템 구축 실습
- Goodbooks-10K 데이터셋을 기반으로 사용자의 도서 선호도를 분석하고 추천 알고리즘을 구현

## 📖 데이터셋

**Goodbooks-10K Dataset**
- 출처 : [Goodbooks-10K Dataset](https://www.kaggle.com/datasets/zygmunt/goodbooks-10k)

**데이터 구성**
- `books.csv`: 도서 메타데이터
- `ratings.csv`: 사용자-도서 평점 정보
- `book_tags.csv`, `tags.csv`: 도서 태그 정보
- `to_read.csv`: 읽을 예정 도서 목록

## 🛠 사용 기술

- **PySpark**
- **MySQL**

## 🧩 실습 단계

1. **데이터 탐색 및 전처리**
   - 결측치/이상치 처리, 통계 분석

2. **MySQL 기반 데이터베이스 설계**
   - 정규화된 테이블 구조 설계 및 로딩

3. **PySpark ETL 파이프라인**
   - MySQL → PySpark 데이터 로딩
   - 데이터 정제 및 처리

4. **추천 시스템 모델링**
   - ALS(Alternating Least Squares) 기반 도서 추천
   - 사용자별 Top-N 추천 리스트 생성
