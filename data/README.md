# 데이터 폴더

이 폴더에 추천 시스템 학습 및 평가에 사용할 데이터를 저장합니다.

## 데이터 형식

일반적으로 다음과 같은 형식의 데이터가 사용됩니다:

### 평점 데이터 (Ratings)
- 컬럼: `user_id`, `item_id`, `rating`, `timestamp`
- 형식: CSV, JSON, Parquet 등

### 사용자 데이터 (Users)
- 컬럼: `user_id`, `age`, `gender`, `occupation` 등
- 형식: CSV, JSON 등

### 아이템 데이터 (Items)
- 컬럼: `item_id`, `title`, `category`, `description` 등
- 형식: CSV, JSON 등

## 샘플 데이터셋

다음과 같은 공개 데이터셋을 사용할 수 있습니다:

- **MovieLens**: 영화 추천 데이터
- **Amazon Reviews**: 제품 리뷰 데이터
- **Last.fm**: 음악 추천 데이터
- **Book-Crossing**: 도서 추천 데이터

## 주의사항

- 대용량 데이터 파일은 `.gitignore`에 의해 Git에서 제외됩니다.
- 개인정보가 포함된 데이터는 반드시 비식별화 처리 후 사용하세요.
- 데이터 출처와 라이선스를 명확히 기록하세요.

